 RUST OVERVIEW

#### 1. What example type of software or apps can you build with Rust?

- Command Line: Whip up a CLI tool quickly with Rust's robust ecosystem. Rust helps you maintain your app with confidence and distribute it with ease
- WebAssembly: Use Rust to supercharge your JavaScript, one module at a time. Publish to npm, bundle with webpack, and you're off to the races
- Networking: Predictable performance. Tiny resource footprint. Rock-solid reliability. Rust is great for network services
- Embedded: Targeting low-resource devices? Need low-level control without giving up high-level conveniences? Rust has you covered.


#### 2. Where do you install rust from?

This webpage: https://www.rust-lang.org/tools/install


#### 3. Where is the place to try out Rust online?

This webpage:
https://play.rust-lang.org/


#### 4. How do you check if you have Rust installed on your system/machine?

By typing out the shell/cmd command:
$ rustc --version
Note: This is also how you check the installed version of your Rust


#### 5. How do you update your Rust version to the latest one?

By inputting the shell/cmd command:
$ rustup update


#### 6. How do you build your Rust project/file?

By running the command:
$ cargo build


#### 7. How do you run your Rust project/file?

By running the command:
$ cargo run


#### 8. How do you test your Rust project/folder?

By running command:
$ cargo test


#### 9. How do you build documentation for your Rust project?

By running command:
$ cargo doc


#### 10. How do you publish your Rust project as a library to crates.io?

By running command:
$ cargo publish


#### 11. Mention a few editor where you can write and develop Rust projects

VS Code, Sublime Text, Atom, IntelliJ Idea, Eclipse, Vim, Emacs, Geany.


#### 12. How do you conveniently generate a new Rust project using cargo?

By running command:
$ cargo new your-rust-project-name


#### 13. Describe the structure of an auto-generated Rust project from cargo

your-rust-proect-name
| - Cargo.toml
|- src
  |- main.rs


#### 14. Describe the Rust project file "Cargo.toml"

It is the manifest file for Rust. It is where you keep metadata for your project, as well as dependencies


#### 15. Where or what file will you write your application code in?

"src/main.rs"
Other files that has suffix ".rs" can also make up part of your Rust application code.


#### 16. Where or what folder will you find all of your Rust's development environment's tools in?

Inside folder structure:
"~/.cargo/bin"
Here, you will find Rust toolchains, such as;
rustc, cargo, and rustup.
Also note that this folder structure will be included in your PATH environment variable when you install Rust, by default, however, if it isn't, then you should include it.


#### 17. How do you know whether or not the folder structure "~/.cargo/bin" has been included inside your PATH environment variable during an installation of rustc?

By running the command:
```
$ rustc --version
```
If this command fails despite having installed rustc, then it means that you have to manually include the folder structure "~/.cargo/bin" inside your PATH environment variable.


#### 18. How do you go about uninstalling Rust from your machine?

By entering the shell/cmd command:
```
$ rustup self uninstall
```


Completed On: Saturday, April 30, 2022.


##   RUST CARGO

#### 1. What is Rust style of indentation?

Indenting with four spaces, instead of a tab, or even two spaces.


#### 2. What does an exclamation mark (!) with a variable name mean in Rust?

It means you are calling a macro.


#### 3. Do macros follow the same rules as functions in Rust?

No, macros don't always follow the same rules as functions in Rust.


#### 4. How many files are emitted when you run the Rust command "rustc main.rs" on Linux and macOS?

One file, namely; main.exe


#### 5. How many files are emitted when you run the Rust command "rustc main.rs" on Windows?

Two files, namely; main.exe & main.pdb


#### 6. Describe the main.pdb file generated by "rustc" compilation command on Windows

It is a file that contains debugging information.


#### 7. What is Rust's build system and package manager?

Cargo


#### 8. As a Rustacean, what might you use Cargo for?

As a tool to manage my Rust project, like;
- building my code (different from compilation)
- downloading the libraries my code would depend on or already depends on
- building libraries my code would depend on or already depends on


#### 9. What are libraries that your code depend on called?

dependencies


#### 10. How do you check for Cargo installment on your machine?

By applying command:
```
$ cargo --version
```
If you get a Cargo version number, it means you have Cargo installed, whereas you'll get an error if you do not have it installed.


#### 11. What files does the "cargo new project-name" generate?

Three files;
- Cargo.toml
- .gitignore
- main.rs nested inside a 'src' top-level folder of your project


#### 12. How do you override the behavior of "cargo new project-name" generating a '.gitignore' file?

By running the Cargo command;
```
$ cargo new --vcs=git
```


#### 13. What does the 'TOML' suffix of the generated 'Cargo.toml' file mean?

It means "Tom's Obvious, Minimal Language. It is a file format.


#### 14. What are packages of code in Rust referred to?

crates


#### 15. What example type of files can be contained inside your top-level project directory alongside the 'src' folder and Cargo's "Cargo.toml" file?

README files, license information, configuration files, and anything else not related to your code.


#### 16. Where does Cargo expect your code files to live in?

Inside the "src" folder inside your top-level project directory.


#### 17. Where does the Cargo command "cargo build" store the resulting compilation or executable?

On Windows, it is: ".target\debug\project_name.exe"
On macOS, it is: ".target/debug/project_name.exe"


#### 18. What additional new file does running Cargo command "cargo build" for the first time create inside your top-level project directory?

Cargo.lock


#### 19. What is the "Cargo.lock" file about?

It keeps track of the exact versions of dependencies in your project for you automatically.


#### 20. What does the command "cargo run" do for you?

It first builds or rebuild your Rust cargo projects, and then run the generated executable of it


#### 21. Why would you consistently run the Cargo command' "cargo check"?

To continually check your work while writing the code, to make sure your program compiles, hence telling you that you have made no mistakes that would lead to a failed compilation process


#### 22. Cargo command "cargo check" compiles your code, but does it also generate or produce an execuatable?

No


#### 23. What Cargo command do you use to build an executable that is most suitable and optimezed for release?
```
$ cargo build --release
```


#### 24. Demonstrate a chain of commands (Git and Cargo commands), which you can use to clone a Rust project from GitHub or any other VCS, and then build the project locally on your machine
```
$ git clone example-vcs.org/someproject
$ cd someproject
$ cargo build
```


Completed On: Tuesday, May 3, 2022.
