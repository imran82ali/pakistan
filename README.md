# First Welcome
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`pakistan = "0.1.0"`

your cargo.toml file should look like this:
```
[package]
name = "hello_world"
version = "0.1.0"
authors = ["imran82ali <code.imranali@gmail.com>"]
edition = "2018"

[dependencies]
pakistan = "0.1.0"
```

In `src/main.rs` you can use like this:

```
use pakistan;
fn main() {
    println!("Hello, world!");
    pakistan::islamabad::piaic();
}
```
following will also work:
```
use pakistan::islamabad::piaic;
fn main() {
    println!("Hello, world!");
    piaic();
    }
```

now `cargo run` for results
