# Spark

A simple cli to input and store your ideas directly with git and without a text editor

Run `spark`, write your idea title and description and your idea will be added a file with your chosen location and commit+push your idea to your git repo. Great when you want to quickly note your next genius idea ✨

![demo](assets/demo.png)

## Usage

- `spark` to write a new idea
- `spark view` to print the idea list using less
- `spark config` to reset the configuration
- `spark help`

## Installation

### macOS

#### Homebrew

`brew install chevalmuscle/spark-idea/spark`

### Other platforms

Install a prebuilt binary from the [releases page][]

### Build from source

0. [Install go](https://golang.org/doc/install)
1. Clone the repo
2. Run `make deps` to install the required dependencies
3. Run `make run`

[releases page]: https://github.com/chevalmuscle/spark/releases/latest
