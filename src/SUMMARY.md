# Rust 程序设计语言(中文版)

## 入门

- [绪论](ch01-00-introduction.md)
    - [安装](ch01-01-installation.md)
    - [Hello, World!](ch01-02-hello-world.md)

- [猜猜看游戏](ch02-00-guessing-game-tutorial.md)

- [通用编程概念](ch03-00-common-programming-concepts.md)
    - [变量及可变性](ch03-01-variables-and-mutability.md)
    - [数据类型](ch03-02-data-types.md)
    - [函数的运行机制](ch03-03-how-functions-work.md)
    - [注释](ch03-04-comments.md)
    - [流控制](ch03-05-control-flow.md)

- [理解所有权](ch04-00-understanding-ownership.md)
    - [什么是所有权？](ch04-01-what-is-ownership.md)
    - [借用和引用](ch04-02-references-and-borrowing.md)
    - [切片](ch04-03-slices.md)

- [结构体](ch05-00-structs.md)
    - [方法](ch05-01-method-syntax.md)

- [枚举和模式匹配](ch06-00-enums.md)
    - [Defining an Enum](ch06-01-defining-an-enum.md)
    - [The `match` Control Flow Operator](ch06-02-match.md)
    - [Concise Control Flow with `if let`](ch06-03-if-let.md)

## Rust 基础知识

- [Modules](ch07-00-modules.md)
    - [`mod` and the Filesystem](ch07-01-mod-and-the-filesystem.md)
    - [Controlling Visibility with `pub`](ch07-02-controlling-visibility-with-pub.md)
    - [Importing Names with `use`](ch07-03-importing-names-with-use.md)

- [Common Collections](ch08-00-common-collections.md)
    - [Vectors](ch08-01-vectors.md)
    - [Strings](ch08-02-strings.md)
    - [Hash Maps](ch08-03-hash-maps.md)

- [Error Handling](ch09-00-error-handling.md)
    - [Unrecoverable Errors with `panic!`](ch09-01-unrecoverable-errors-with-panic.md)
    - [Recoverable Errors with `Result`](ch09-02-recoverable-errors-with-result.md)
    - [To `panic!` or Not To `panic!`](ch09-03-to-panic-or-not-to-panic.md)

- [Generic Types, Traits, and Lifetimes](ch10-00-generics.md)
    - [Generic Data Types](ch10-01-syntax.md)
    - [Traits: Defining Shared Behavior](ch10-02-traits.md)
    - [Validating References with Lifetimes](ch10-03-lifetime-syntax.md)

- [Testing](ch11-00-testing.md)
    - [Writing tests](ch11-01-writing-tests.md)
    - [Running tests](ch11-02-running-tests.md)
    - [Test Organization](ch11-03-test-organization.md)

- [An I/O Project](ch12-00-an-io-project.md)
    - [Accepting Command Line Arguments](ch12-01-accepting-command-line-arguments.md)
    - [Reading a File](ch12-02-reading-a-file.md)
    - [Improving Error Handling and Modularity](ch12-03-improving-error-handling-and-modularity.md)
    - [Testing the Library's Functionality](ch12-04-testing-the-librarys-functionality.md)
    - [Working with Environment Variables](ch12-05-working-with-environment-variables.md)
    - [Writing to `stderr` instead of `stdout`](ch12-06-writing-to-stderr-instead-of-stdout.md)

## Rust 编程思想

- [Functional Language Features in Rust](ch13-00-functional-features.md)
    - [Closures](ch13-01-closures.md)
    - [Iterators](ch13-02-iterators.md)
    - [Improving our I/O Project](ch13-03-improving-our-io-project.md)
    - [Performance](ch13-04-performance.md)

- [More about Cargo and Crates.io](ch14-00-more-about-cargo.md)
    - [Release Profiles](ch14-01-release-profiles.md)
    - [Publishing a Crate to Crates.io](ch14-02-publishing-to-crates-io.md)
    - [Cargo Workspaces](ch14-03-cargo-workspaces.md)
    - [Installing Binaries from Crates.io with `cargo install`](ch14-04-installing-binaries.md)
    - [Extending Cargo with Custom Commands](ch14-05-extending-cargo.md)

- [Smart Pointers](ch15-00-smart-pointers.md)

- [Concurrency](ch16-00-concurrency.md)

- [Is Rust OOP?](ch17-00-oop.md)

## 高级主题

- [Patterns](ch18-00-patterns.md) (perhaps an appendix?)

- [More Lifetimes](ch19-00-more-lifetimes.md) (perhaps merge this into advanced type system features?)

- [Advanced Type System Features](ch20-00-advanced-types.md) (perhaps called "Advanced Traits"?)

- [Appendix](appendix-00.md)
    - [Keywords](appendix-01-keywords.md)
    - [Operators](appendix-02-operators.md)
    - [Derivable Traits](appendix-03-derivable-traits.md)
    - [Nightly Rust](appendix-04-nightly-rust.md)
    - [Macros](appendix-05-macros.md)
