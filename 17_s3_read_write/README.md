# S3 Read Write
Create a cli tool that reads data from and writes data to an AWS S3 bucket!

<br/>

## Backstory
You have data!

But, where to put it? 🤔

Let's suppose you (or your boss / company) has decided they want to store it in an AWS s3 bucket since it's a very cheap and convenient way to store data.

So, you want to interact with s3 buckets via your command line tools! 

<br/>

## The Exercise
Write a cli tool that allows you to read and write s3 records.

It's up to you to decide if you would like to accept a "command" as the first a cli tool argument, use an inquire "select" input for the user to choose, or something else!

Suppose we have a single mongo collection named _MyBucket_ with documents that look something like this:

We want to be able to do these s3 interactions:

<br/>

### Write Operations

- create(newDoc) - inserts a blob of content into the s3 bucket

<br/>

- replace(_id, newDoc) - takes an _id input and completely replaces the existing content at that location

<br/>

- delete(_id) - takes an _id input, deletes the content with that _id

<br/>

### Read Operations

- read(_id) - takes an _id input and returns the content blob 

<br/>

## Tests
Ensure that your unit tests do NOT actually call to AWS.

For your integration tests, run a local instance of s3, run your tests that call all your individual functions, and expect the correct data to be in the local bucket.

<br/>

## Skills Practiced

- Storing and reading secrets

- Connecting to an \[S3\] bucket

<br/>

## Bonus

- Try other "data lake" or "data warehouse" storage types such as Snowflake or Databricks Lakehouse