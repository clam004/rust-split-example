# Growing a Rust project

Example of how to break apart a rust project to make it more modular and grow it while keeping it manageable. The first commits are in order of growth.

```
git clone https://github.com/clam004/rust-split-example.git
cd rust-split-example
rust-split-example $ cargo build
```

```
   Compiling de_lib v0.1.0 (/Users/rust-split-example/de_lib)
   Compiling de_cli v0.1.0 (/Users//rust-split-example/de_cli)
    Finished dev [unoptimized + debuginfo] target(s) in 0.65s
```

a `target` folder will appear

```
rust-split-example $ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.02s
     Running `target/debug/de_cli`
first one: 2, -1 = -2
second one: 4, -2 = -8
third one: 8, -4 = -32
```





