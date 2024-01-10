# Integration Tests in Rust 

This repository provides a comprehensive example of different types of testing in Rust using the [Cargo](https://doc.rust-lang.org/cargo/) package manager. The application demonstrates writing unit tests, integration tests, and documentation tests.

This example includes a Rust application with a simple module (src/lib.rs) containing unit tests, integration tests in a separate file (tests/pizzas.rs), and documentation tests embedded in the Rust doc comments.

## Features

- Writing and running unit tests.
- Creating and executing integration tests.
- Incorporating documentation tests for comprehensive testing coverage.

## Getting Started

### Prerequisites

Make sure you have Rust and Cargo installed on your system. If not, you can install them by following the instructions on the [official Rust website](https://www.rust-lang.org/learn/get-started).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/eduardoraider/rust-integration-tests.git
   ```

2. Change into the project directory:

   ```bash
   cd rust-integration-tests
   ```

3. Build the application using Cargo:

   ```bash
   cargo build
   ```

### Usage

1. Run unit tests:

   ```bash
   cargo test
   ```
   
2. Run unit tests:

   ```bash
   cargo test --test pizzas
   ```
   
3. Run documentation tests:

   ```bash
   cargo test --doc
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

---

#### by Eduardo O Raider
🛠 🥋 **Software Engineer**