# minigrep
I/O project from the Rust Programming Language book. See https://doc.rust-lang.org/book/ch12-00-an-io-project.html for more details.

## Usage

`cargo run -- <query> <file>`

Example: `cargo run -- the poem.txt`

An environment variable can be used to control case sensitivity. By default, queries are case sensitive.

Example: `IGNORE_CASE=1 cargo run -- the poem.txt`

This project includes an enhancement to accept a command line option `-i` to ignore casing. This option takes precedence over the environment variable.

Example: `cargo run -- the poem.txt -i`
