# rust-cli-exercises
Little exercises for learning Rust and building awesome cli tools! ⭐️

<br/>

## What's Here
This repo is a collection of many extremely small Rust projects.

This idea is to break down otherwise _scary_ Rust code into small, approachable, and easily testable little functions.

<br/>

## Running The Projects
Each folder in the root directory contains a completely independent Rust project meant to be run with `cargo`, which can be installed via [rustup](https://rustup.rs/).

First ensure you have rust and cargo installed:
```bash
cargo --version
```

<br/>

You can then navigate into each project folder and run the cli tool:
```
cargo run
```

<br/>

You can also run the automated tests:
```
cargo test
```

<br/>

_Note: This runs both unit tests and integration tests!_

<br/>

In addition to just running the tests, you can check code coverage:
```
cargo tarpaulin --out Html
```

Then view the `tarpaulin-report.html` file in a browser.

You can also run _mutation tests_ to test your tests using libraries such as [cargo-mutants](https://crates.io/crates/cargo-mutants)!

<br/>

## Work Through In any Order
The numbers prefixing each folder are meant to be a recommended path to following in exploring these projects, but feel free to jump around as they are completely independent of each other!

Each project has a README that explains the problem to be solved and skills practiced.

<br/>

## Anatomy of An Exercise

Each exercise will have a README.md file in the root of the project with these sections:

- ## Title
     Name for the project with a little one sentence blurb.

<br/>

- ## Backstory
    An imaginary real world situation where this code could be useful.

<br/>

- ## The Exercise
    The goal / success criteria of what you need to build.

<br/>

- ## Tests
    Some suggestions around what unit and integration tests to write.

<br/>

- ## Skills Practiced
    Specific "toolbox" skills used to complete the exercise.

<br/>

- ## Bonus
    Some ideas for how to take the exercise further and expand on it.

<br/>

- ## Hints
    Located in a Hints.md file, these are meant to get you going in the right direction without completely giving away the solution.

<br/>

## Build Your Own "Rust Toolbox"
By building little Rust applications like these you are documenting how to accomplish and test different things you might want a command line utility to do.

If you starting building your own portfolio of Rust cli tools then one day when you _actually want to solve some business problem_ with Rust you won't be starting from scratch and can use some of your old code and/or experiences to help you!

<br/>

## Why Rust For CLI Tools?

There are just a few reasons why Rust makes an excellent language for writing command line utilities:

- ### Fast Startup & Execution Time
    Often times there is a delay on startup and during heavy processing for languages with a garbage collector.
    
    Since Rust CLI programs do not have to boot up a vm or gc they can extremely fast, thus saving developer time, energy, and happiness in addition to company dollars!

- ### Low Level Control With A Nice Syntax
    
    The borrowing, lifetimes, and `mut` keyword gives the programmer very fine control over memory usage  

- ### Cargo Is Awesome

    Cargo makes it very easy to build and deploy cli tools, and not just to cargo- you can also publish your super efficient binary to other package managers like npm!

- ### Coding In Rust Is Fun!!
    
    Once you get the hang of it you may find that you actually really enjoy working on projects in Rust. There is a reason why it is voted the "Most Loved Programming Language" on the Stack Overflow survey every year! 

<br/>

## Solutions
If you really get stuck and want to see Jim's solutions, see the [rust-cli-examples](https://github.com/JimLynchCodes/rust-cli-examples) repo.

It is highly recommended to work through them on your own because by just reading the final code you are missing out on seeing all the compiler and linter errors along the way that led the code to end up this way...

<br/>

## Contributing

Have a cool little cli tool you want to show off to others? Feel free to add a pull request! Also, feel free to open an issue just to discuss before hand or if you have any questions about the code / projects here. 

<br/>

## MIT Open Source

Feel free to copy, modify, or distribute this code for your own personal or commercial use. Use at your own risk!

<br/>

---

<br/>

Thanks for stopping by! 🦀
