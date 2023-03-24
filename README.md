# Automachina

Lobana Abstract Computers  

[![License](https://www.gnu.org/graphics/agplv3-with-text-162x68.png)](./LICENSE.txt)


## Contents  

* [Installation](#installation)
* [Usage](#usage)
* [Documentation](#documentation)
* [Examples](#examples)
* [Support](#support)
* [Contribute](#contribute)
* [Acknowledgements](#acknowledgements)
* [Donate](#donate)
* [License](#license)

## Installation  

* [Cargo](#cargo)
* [Git](#git)

### Cargo

The recommended way to install the library is via Cargo, Rust's package manager. To install the library using Cargo, follow these steps:

1. Open terminal or command line interface on your system.

2. Navigate to your project directory.

    ```bash
        cd <project-directory>
    ```

3. Install using Cargo.

    ```bash
        cargo install automachina
    ```

4. Wait for Cargo to download and build the library. This may take some time depending on server load and your internet connection speed.

5. Once Cargo has finished building the library, you should be able to use it in your project.

### Git

If you prefer to install the library from source, you can do so by cloning the library's Git repository and building it manually. To install the library from source, follow these steps:

1. Open terminal or command line interface on your system.

2. Navigate to the directory where you want to clone the repository.

    ```bash
        cd <directory>
    ```

3. Clone the library's Git repository.

    ```bash
        git clone https://github.com/karansinghlobana/automachina.git
    ```

4. Wait for Github to download the library. This may take some time depending on server load and your internet connection speed.

5. Navigate to the directory containing the library's source code.

    ```bash
            cd automachina
    ```

6. Build the library using Cargo.

    ```bash
            cargo build
    ```

7. Wait for Cargo to download dependencies and build the library. This may take some time depending on server load, your internet connection speed and your system's computing power.


8. Once Cargo has finished building the library, you should be able to use it in your project.

## Usage  

* [Add Module](#add-module)
* [Update Module](#update-module)
* [Use Module](#use-module)

### Add Module

Before you can use the library in your project, you need to import it. To do this, add the following line to your project's `Cargo.toml` file.

```toml
    [dependencies]
    automachina = "0.1.0"
```
You can find the latest version of the library on the library's repository page.

### Update Module

After you've added the library to your `Cargo.toml` file, run the following command to download and install the library.

```bash
    cargo update
```

### Use Module

Once you've imported the library into your project, you can use it in your code. Here's an example of how to use the library's functionality.

```rust
use automachina::Computer;
use automachina::architectures::Architecture;
use automachina::machines::Machine;
use automachina::programs::Program;

fn main() {

    let architecture = Architecture::new();
    let machine = Machine::new(architecture);
    let computer = Computer::new(machine);

    let program = Program::new();
    computer.execute(program);

}

```

## Documentation  



## Examples  

## Support  

## Contribute  

## Acknowledgements  

## Donate  

## License 

Automachina: Lobana Abstract Computers
Copyright (C) 2023 Karan Singh Lobana

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
[GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html) for more details.

You should have received a copy of the [GNU Affero General Public License](./LICENSE.txt)
along with this program.  If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).
