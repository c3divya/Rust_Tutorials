# Rust Tutorials 

[RUST Link](https://doc.rust-lang.org/book/ch01-02-hello-world.html)

## Chatper 1 Getting Started with Rust

Start by Installing Rust. You can use rustup, the command line tool to install rust. To dowaload you'll need an internet connection

## 1. Installing rustup for Linux and macOS
```
$ curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh
```

```
Rust is installed now! Great
```

After installation run the below command
```
source "$HOME/.cargo/env"
```

Check the weather rust is installed or not
```
rustc --version
```

You will also need a linker , a program that Rust uses to join all the compiled file together. 
It is likely you already have one. If you get linker errors, you should install a C compiler, which will typically include a linker. A C compiler is also useful because some common Rust packages depend on C code and will need a C compiler.

On MacOS you can get a C compiler by running

```
xcode-select --install
```

[Link to Install on windows](https://doc.rust-lang.org/book/ch01-01-installation.html)

