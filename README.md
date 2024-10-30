# minigrep_rust

`minigrep_rust` is a simple command-line tool written in Rust that helps you search for lines containing a specified substring within a file. It outputs a list of lines that match the given substring, making it a useful tool for quick text searching.

## Features

-  Search for a substring within a file.
-  Outputs all lines that contain the specified substring.
-  Simple and efficient command-line interface.

## Installation

To use `minigrep_rust`, you need to have Rust installed on your system. You can install Rust using [rustup](https://www.rust-lang.org/learn/get-started).

Clone the repository and build the project:

```bash
git clone https://github.com/yourusername/minigrep_rust.git
cd minigrep_rust
cargo build --release
```

## Usage
After building the project, you can use the tool by running the following command in your terminal:

```bash
cargo run -- <substring> <file_path>
```

#### Example
```bash
cargo run -- body poem.txt
```

Output:
```bash
I'm nobody! Who are you?
Are you nobody, too?
How dreary to be somebody!
```

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

