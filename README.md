   ##RUST OVERVIEW

1. What example type of software or apps can you build with rust?

- Command Line: Whip up a CLI tool quickly with Rust's robust ecosystem. Rust helps you maintain your app with confidence and distribute it with ease
- WebAssembly: Use Rust to supercharge your JavaScript, one module at a time. Publish to npm, bundle with webpack, and you're off to the races
- Networking: Predictable performance. Tiny resource footprint. Rock-solid reliability. Rust is great for network services
- Embedded: Targeting low-resource devices? Need low-level control without giving up high-level conveniences? Rust has you covered.


2. Where do you install rust from?

This webpage: https://www.rust-lang.org/tools/install


3. Where is the place to try out Rust online?

This webpage:
https://play.rust-lang.org/


4. How do you check if you have Rust installed on your system/machine?

By typing out the shell/cmd command:
$ rustc --version
Note: This is also how you check the installed version of your Rust


5. How do you update your Rust version to the latest one?

By inputting the shell/cmd command:
$ rustup update


6. How do you build your Rust project/file?

By running the command:
$ cargo build


7. How do you run your Rust project/file?

By running the command:
$ cargo run


8. How do you test your Rust project/folder?

By running command:
$ cargo test


9. How do you build documentation for your Rust project?

By running command:
$ cargo doc


10. How do you publish your Rust project as a library to crates.io?

By running command:
$ cargo publish


11. Mention a few editor where you can write and develop Rust projects

VS Code, Sublime Text, Atom, IntelliJ Idea, Eclipse, Vim, Emacs, Geany.


12. How do you conveniently generate a new Rust project using cargo?

By running command:
$ cargo new your-rust-project-name


13. Describe the structure of an auto-generated Rust project from cargo

your-rust-proect-name
| - Cargo.toml
|- src
  |- main.rs


14. Describe the Rust project file "Cargo.toml"

It is the manifest file for Rust. It is where you keep metadata for your project, as well as dependencies


15. Where or what file will you write your application code in?

"src/main.rs"
Other files that has suffix ".rs" can also make up part of your Rust application code.


16. Where or what folder will you find all of your Rust's development environment's tools in?

Inside folder structure:
"~/.cargo/bin"
Here, you will find Rust toolchains, such as;
rustc, cargo, and rustup.
Also note that this folder structure will be included in your PATH environment variable when you install Rust, by default, however, if it isn't, then you should include it.


17. How do you know whether or not the folder structure "~/.cargo/bin" has been included inside your PATH environment variable during an installation of rustc?

By running the command:
$ rustc --version
If this command fails despite having installed rustc, then it means that you have to manually include the folder structure "~/.cargo/bin" inside your PATH environment variable.


18. How do you go about uninstalling Rust from your machine?

By entering the shell/cmd command:
$ rustup self uninstall


Completed On: Saturday, April 30, 2022.
