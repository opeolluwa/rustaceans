# Project Setup

To begin, we'll create a new Rust binary with `Cargo`
Cargo is the Rust package manager. Think of it as [npm](https://www.npmjs.com/) as seen in the Node.js applications, [pip](https://pypi.org/project/pip/) for Python, or [composer](https://getcomposer.org/) for PHP. Cargo simple let you manage your Rust application, to build binary, to run you application. See the [Cargo documentation](https://doc.rust-lang.org/cargo/index.html) for more information.

```
cargo new --bin thunderstorm
```

This will create a folder called thunderstorm in the current directory. The folder will contain the following files:

-  `Cargo.toml`
-  `src/main.rs`

To be sure everything is working right, execute the command:`cargo run` This will run the binary and print the following message:

```bash

   Compiling thunderstorm v0.1.0 (/home/drizzle/workspace/rustaceans/examples/thunderstorm)
    Finished dev [unoptimized + debuginfo] target(s) in 1.83s
     Running `target/debug/thunderstorm`
Hello, world!

```

We're all set to go on with the tutorial!

## Install require crates

Crates are Rust libraries that can be used in your project. Think of them as package or

For this tutorial, we'll need to install the [clap](https://crates.io/crates/clap) crate. The clap crate is a command line parsing crate that is used to parse the command line arguments.
So go on run the following command to install the clap crate:

```bash
cargo add clap
```
