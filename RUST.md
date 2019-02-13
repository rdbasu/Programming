## RUST
[Rust Programming Language](https://www.rust-lang.org/)


Rust empowers you to reach farther, to program with confidence in a wider variety of domains than you did before.
Take, for example, **“systems-level”** work that deals with low-level details of memory management, data representation, and concurrency.

**speed and memory usage**

## low-level systems programming
### CLI apps, web servers,...

**High-level ergonomics and low-level control**

*Rust gives you the option to control low-level details (such as memory usage) without all the hassle traditionally associated with such control.*

*In Rust, the compiler plays a gatekeeper role by refusing to compile code with these elusive bugs, including concurrency bugs.*

## Dependency Manager
Cargo, the included dependency manager and build tool, makes adding, compiling, and managing dependencies painless and consistent across the Rust ecosystem.

## Installation
`rustup` a command line tool for managing Rust versions and associated tools

```
curl https://sh.rustup.rs -sSf | sh
```

```
LM-SJN-XXXXXXXX:Documents robasu$ curl https://sh.rustup.rs -sSf | sh
info: downloading installer

Welcome to Rust!

This will download and install the official compiler for the Rust programming 
language, and its package manager, Cargo.

It will add the cargo, rustc, rustup and other commands to Cargo's bin 
directory, located at:

  /Users/robasu/.cargo/bin

This path will then be added to your PATH environment variable by modifying the
profile files located at:

  /Users/robasu/.profile
  /Users/robasu/.bash_profile

You can uninstall at any time with rustup self uninstall and these changes will
be reverted.

Current installation options:

   default host triple: x86_64-apple-darwin
     default toolchain: stable
  modify PATH variable: yes

1) Proceed with installation (default)
2) Customize installation
3) Cancel installation
>1

info: syncing channel updates for 'stable-x86_64-apple-darwin'
info: latest update on 2019-01-17, rust version 1.32.0 (9fda7c223 2019-01-16)
info: downloading component 'rustc'
 64.5 MiB /  64.5 MiB (100 %)  13.6 MiB/s ETA:   0 s                
info: downloading component 'rust-std'
 49.2 MiB /  49.2 MiB (100 %)  14.7 MiB/s ETA:   0 s                
info: downloading component 'cargo'
info: downloading component 'rust-docs'
info: installing component 'rustc'
info: installing component 'rust-std'
info: installing component 'cargo'
info: installing component 'rust-docs'
info: default toolchain set to 'stable'

  stable installed - rustc 1.32.0 (9fda7c223 2019-01-16)


Rust is installed now. Great!

To get started you need Cargo's bin directory ($HOME/.cargo/bin) in your PATH 
environment variable. Next time you log in this will be done automatically.

To configure your current shell run source $HOME/.cargo/env
LM-SJN-XXXXXXXX:Documents robasu$ 
```
*To check whether you have Rust installed correctly*
```
LM-SJN-XXXXXXXX:~ robasu$ rustc --version
rustc 1.32.0 (9fda7c223 2019-01-16)
LM-SJN-XXXXXXXX:~ robasu$ 
```

*Local Documentation*
```
rustup doc
```

## Hello World

A new file called **helloworld.rs**

*Rust files always end with the **.rs** extension*

