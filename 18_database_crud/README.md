# Mongo CRUD
Create a cli tool that creates, reads, updates, and deletes data to and from a MongoDB database!

<br/>

## Backstory
Being able to read from and write to a databases is such an empowering skill that we had to create an example here!

Since MongoDB is a fast, scalable, and easy to use database your company has decided to use it, and now you want to interact with it via your command line tools! 

<br/>

## The Exercise
Write a cli tool that allows you to create, read, update, and delete records.

It's up to you to decide if you would like to accept a "command" as the first a cli tool argument, use an inquire "select" input for the user to choose, or something else!

Suppose we have a single mongo collection named _Users_ with documents that look something like this:

```ts
{
    _id: ObjectId,
    name: String,
    favoriteInteger: uint,
}
```

_Note: _id is the idiomatic name of the primary key field for MongoDb_

We want to be able to do these db interactions:

### Create Operations

- create(newDoc) - inserts a blob of data as a document into the collection

### Read Operations

- read() - takes no arguments and returns the entire collection (Note: see bonus for a more scalable verion!)
- read(_id) - takes an _id input and returns the document 

### Update Operations

- update(_id, ..newFields) - takes an _id input and some list of key value pairs representing the document fields to be updated and the new values
- replace(_id, newDoc) - takes an _id input and completely replaces the existing document with newDoc
- 
### Delete Operations

- delete(_id) - takes an _id input, deletes the document with that _id

<br/>

## Tests
Ensure that your unit tests do NOT actually call to a real database.

For your integration tests, run a local mongo instance, run your tests that call all your individual functions, and expect the correct data to be in the database.

<br/>

## Skills Practiced

- Storing and reading secrets

- Connecting to a \[MongoDb\] database

- Various querying techniques 

<br/>

## Bonus!
- Build a read query that implements cursor pagination

- When reading an individual document, incorprate a mongo "projection parameter" to efficiently read only a subset of fields from the document  