# Automachina

Lobana Abstract Computers  

![docs.rs](https://img.shields.io/docsrs/automachina?style=for-the-badge)
![Docker Automated build](https://img.shields.io/docker/automated/karansinghlobana/automachina?style=for-the-badge)
![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline-status/automachina?branch=main&style=for-the-badge)
![Gitlab code coverage](https://img.shields.io/gitlab/pipeline-coverage/automachina?branch=main&style=for-the-badge)
![Scrutinizer coverage (GitLab)](https://img.shields.io/scrutinizer/quality/gl/automachina/karansinghlobana/automachina/main?style=for-the-badge)
![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/karansinghlobana/automachina?style=for-the-badge)
![GitLab language count](https://img.shields.io/gitlab/languages/count/automachina?style=for-the-badge)
![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/karansinghlobana/automachina?sort=date&style=for-the-badge)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/karansinghlobana/automachina?style=for-the-badge)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/karansinghlobana/automachina?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/karansinghlobana/automachina?style=for-the-badge)
![Lines of code](https://img.shields.io/tokei/lines/github/karansinghlobana/automachina?style=for-the-badge)
![Crates.io](https://img.shields.io/crates/d/automachina?style=for-the-badge)
![GitHub all releases](https://img.shields.io/github/downloads/karansinghlobana/automachina/total?style=for-the-badge)

[![License](https://www.gnu.org/graphics/agplv3-with-text-162x68.png)](./LICENSE.txt)


## Contents  

* [Installation](#installation)
    * [Cargo](#cargo)
    * [Git](#git)
* [Usage](#usage)
    * [Add crate](#add-crate)
    * [Update crate](#update-crate)
    * [Use crate](#use-crate)
* [Documentation](#documentation)
    * [Use Documentation](#use-documentation)
    * [Edit Documentation](#edit-documentation)
* [Examples](#examples)
* [Support](#support)
* [Contribute](#contribute)
    * [Pull Requests](#pull-requests)
    * [Pull Request Guidelines](#pull-request-guidelines)
    * [API Guidelines](#api-gudelines)
    * [Code Style Guidelines](#code-style-guidelines)
    * [Ways to Contribute](#ways-to-contribute)
        * [Requests](#requests)
            * [Comment](#comment)
            * [Feature](#feature)
        * [Report Bugs](#report-bugs)
        * [Edit Code](#edit-code)
            * [Fix Bugs](#fix-bugs)
            * [Add Feature](#add-feature)
            * [Remove Feature](#remove-feature)
            * [Refactor](#refactor)
        * [Edit Documentation](#edit-documentation)
        * [Community Support](#donate)
        * [Donate](#donate)
    * [Code of Conduct](#code-of-conduct)
* [Acknowledgements](#acknowledgements)
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

* [Add crate](#add-crate)
* [Update crate](#update-crate)
* [Use crate](#use-crate)

### Add crate

Before you can use the library in your project, you need to import it. To do this, add the following line to your project's `Cargo.toml` file.

```toml
    [dependencies]
    automachina = "0.1.0"
```
You can find the latest version of the library on the library's repository page.

### Update crate

After you've added the library to your `Cargo.toml` file, run the following command to download and install the library.

```bash
    cargo update
```

### Use crate

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

The documentation for this project is available in multiple formats. These formats include:

* `README.md`: This is the primary source of documentation for this project. It provides an overview of the project, installation instructions, usage instructions, contribution guidelines, and other relevant information. It is recommended that you start here.
* **Code Documentation**: The code is extensively documented using inline comments. This documentation provides an in-depth explanation of the implementation details of the project. To generate this documentation, you can use tools like Rustdoc.
* **Wiki**: The project also has a wiki that provides detailed information about the project, including architecture, design decisions, and implementation details. You can access the wiki by visiting the project's GitHub page.

### Use Documentation

To use the documentation effectively, it is recommended that you start with the `README.md` file. This file provides a brief overview of the project, installation instructions, and usage instructions.

If you need more detailed information, you can refer to the code documentation. The code documentation provides an in-depth explanation of the implementation details of the project.

If you need information about the architecture, design decisions, or implementation details, you can refer to the wiki.

### Edit Dcoumentation

If you find any issues with the documentation or want to contribute to the documentation, you can do so in the following ways:

* **Raise an Issue**: If you find any issues with the documentation, you can raise an issue on the project's GitHub page. This will alert the project maintainers, who can then address the issue.
* **Submit a Pull Request**: If you want to contribute to the documentation, you can submit a pull request with the changes you want to make. The project maintainers will review your changes and merge them if they meet the project's standards.

It is important to note that the documentation is as important as the code itself, and any contributions to the documentation are highly appreciated.


## Examples  

### Architecture

```rust
use automachina::architectures::Architecture;
use automachina::architectures::registers::Register;
use automachina::architectures::stacks::Stack;
use automachina::architectures::instructions::Instruction;
use automachina::architectures::labels::Label;
use automachina::architectures::directives::Directive;
```

### Machine

```rust
use automachina::machines::Machine;
```

### Program

```rust
use automachina::programs::Program;
```

### Computer

```rust
use automachina::Computer;
```

## Support  

If you are facing any issues or have any questions about this project, there are several ways to seek support:

1. **Consult the README.md file**: The README.md file contains information on how to install and use the library, as well as how to report bugs and contribute to the project.
2. **Check the documentation**: The documentation provides a detailed overview of the library's features and usage. It may also contain troubleshooting tips and examples.
3. **Raise an issue on GitHub**: If you encounter a bug or have a question about the library, you can open an issue on the project's GitHub repository. Be sure to provide as much detail as possible, including steps to reproduce the issue and relevant error messages.
4. **Join the community**: Consider joining online forums, mailing lists, or chat rooms dedicated to the library or the programming language in which it is written. These communities can be a valuable source of support and knowledge.
5. **Contact contributors**: If you are unable to find a solution to your issue through the above methods, you can try reaching out to the project contributors directly. You can contact me at [karansinghlobana@protonmail.com](mailto:karansinghlobana@protonmail.com)

## Contribute  

* [Pull Requests](#pull-requests)
    * [Pull Request Guidelines](#pull-request-guidelines)
    * [API Guidelines](#api-gudelines)
    * [Code Style Guidelines](#code-style-guidelines)
* [Ways to Contribute](#ways-to-contribute)
    * [Requests](#requests)
        * [Comment](#comment)
        * [Feature](#feature)
    * [Report Bugs](#report-bugs)
    * [Edit Code](#edit-code)
        * [Fix Bugs](#fix-bugs)
        * [Add Feature](#add-feature)
        * [Remove Feature](#remove-feature)
        * [Refactor](#refactor)
    * [Edit Documentation](#edit-documentation)
    * [Community Support](#donate)
    * [Donate](#donate)
* [Code of Conduct](#code-of-conduct)

### Pull Requests

We welcome contributions to this library! If you're interested in contributing, please follow these steps:

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
3. Create a new branch for your changes.
4. Make your changes, committing as you go.
5. Push your changes to your forked repository.
6. Submit a pull request to the original repository.

We'll review your pull request as soon as possible and provide feedback if needed. We appreciate your contributions to the library!

#### Pull Request Guidelines  

When submitting a pull request, please ensure that:

1. Your code adheres to our code style guidelines. We use [Rustfmt](https://rust-lang.github.io/rustfmt) to enforce consistent formatting across the codebase. Please run `cargo fmt` to format your changes before submitting your pull request.
2. Your changes don't break existing functionality. Before submitting your changes, please ensure that all existing tests pass, and consider writing additional tests for any new functionality.
3. Your changes are well-documented, including any changes to public API. Please make sure to update any relevant documentation, including README.md, examples, and API documentation, to reflect your changes.
4. You've added tests for any new functionality. We require tests for all new functionality to ensure that it works as expected and doesn't break existing functionality.

In addition to these guidelines, we ask that all pull requests adhere to the API guidelines.

#### API Guidelines  

We strive to maintain a stable API for the library, so that our users can depend on it without worrying about breaking changes. To achieve this, we follow these guidelines for our public API:

1. **Stability**: We mark our API as stable when we're confident that it's unlikely to change in a breaking way. Once an API is marked stable, we'll maintain backwards compatibility for the foreseeable future. When adding new functionality, we'll usually add it to the library as an unstable feature first, and only mark it stable once we're confident that it's ready for prime time.
2. **Backwards compatibility**: We avoid making breaking changes to our stable API whenever possible. If we need to make a breaking change, we'll follow Rust's [Semantic Versioning](https://semver.org/) guidelines, which means that we'll bump the major version number of the library to indicate that the API has changed in a backwards-incompatible way. We'll also provide migration guides to help users upgrade to the new version.
3. **Documentation**: We provide clear and comprehensive documentation for all public API. This includes not just the API reference documentation, but also examples, guides, and tutorials to help users get started with the library. We also strive to write documentation that's easy to understand, even for users who are new to Rust or programming in general.
4. **Consistency**: We aim to keep our API consistent and easy to use. This means following established Rust conventions and idioms, as well as avoiding unnecessary complexity or boilerplate. We also avoid exposing implementation details or internal state through our public API.

In addition to these guidelines, we ask that all pull requests adhere to the code style guidelines.

#### Code Style Guidelines

We believe that clean, readable, and consistent code is important for the long-term maintainability of our library. To achieve this, we follow these guidelines for our code style:

1. **Formatting**: We use the default Rust formatting guidelines as provided by `rustfmt`. This helps ensure that our code is consistently formatted and easy to read.
2. **Naming conventions**: We follow the Rust naming conventions as outlined in the official Rust documentation. This includes using `snake_case` for variables and functions, `PascalCase` for types and structs, and `SCREAMING_SNAKE_CASE` for constants.
3. **Comments**: We use comments to help explain our code and make it more readable. We strive to write comments that are clear, concise, and add value to the code. We also avoid commenting code that's self-explanatory or obvious.
4. **Function size**: We aim to keep our functions small and focused. This helps improve code readability and maintainability. Generally, we try to limit function size to no more than 50 lines of code. If a function is getting too complex, we consider refactoring it into smaller, more focused functions.
5. **Error handling**: We use Rust's built-in error handling mechanisms, such as `Result` and `Option`, to handle errors and unexpected situations. We avoid throwing exceptions or using error codes, and instead use Rust's powerful type system to provide clear and concise error messages. We also aim to provide helpful error messages that help users diagnose and fix problems quickly.
6. **Code modularity**: We strive to keep our code modular and easy to understand. This means breaking up our code into small, reusable components, and avoiding large, monolithic functions or modules. We also aim to write code that's easy to test and maintain, so that we can catch bugs and issues early in the development process.
7. **Testing**: We believe that writing tests is essential for ensuring the quality and correctness of our code. We use Rust's built-in testing framework to write unit tests for our code. We aim to write tests that cover all critical functionality, as well as edge cases and error scenarios. We also strive to write tests that are easy to understand and maintain.

### Ways to Contribute

#### Requests

If you have an idea for a new feature or improvement to the project, or if you encounter a bug or issue, there are a few different ways you can make a request.

##### Comment

If you have any questions or feedback about the project, you can request a comment. This can be done in multiple ways:

* You can open an issue in the repository and leave a comment describing your question or feedback.
* You can also comment on an existing issue if you feel that you have some relevant information to add.

When requesting a comment, please provide as much detail as possible about your question or feedback. This will help the project maintainers understand your request and respond appropriately.

##### Feature

If you feel that something is missing from the project or can be improved, you can suggest a new feature. This can be done in multiple ways:

* You can open an issue in the repository and describe the feature you would like to see.
* If the feature has already been suggested, you can upvote the issue or add more information to it.
* If you have a clear idea of how the feature should work and you are willing to work on it, you can create a pull request that implements the feature.

When requesting a feature, please provide as much detail as possible about what you would like to see. This can include use cases, examples, and any other relevant information. This will help the project maintainers understand your suggestion and evaluate its feasibility.

#### Report Bugs

If you encounter any bugs or issues while using the project, we encourage you to report them to us. Reporting bugs helps us improve the quality and reliability of the project for all users.

To report a bug, you can open an issue in the project's repository on GitHub. When you open the issue, please provide as much detail as possible about the bug you have encountered. This should include:

* A description of what happened and what you expected to happen
* Any error messages or logs that were generated
* Steps to reproduce the bug, if possible

If you have any additional information that you think might be helpful in diagnosing or fixing the bug, please include that as well.

Once you have reported a bug, a member of the project team will review the issue and respond as soon as possible. Please be patient and understand that it may take some time to investigate and resolve the issue.

If you are able to provide a fix for the bug, you can also submit a pull request with the fix. See the [Edit Code](#edit-code) section for more information on how to contribute code changes to the project.

#### Edit Code
Contributing code changes to the project is a great way to help improve its functionality and add new features. When contributing code changes to the project, please ensure that your code adheres to the project's coding standards and follows any established APIs. See the [Code Style Guidelines](#code-style-guidelines) and [API Guidelines](#api-guidelines) sections for more information.

Before submitting a pull request, please ensure that you have tested your changes thoroughly and that they do not introduce any new issues or bugs. If possible, please include automated tests with your changes to help ensure that they continue to work as expected in the future.

Once you have submitted a pull request, a member of the project team will review the changes and provide feedback. Please be patient and understand that it may take some time to review and merge your changes.
##### Fix Bugs

If you have encountered a bug or issue with the project, and you have identified a way to fix it, you can submit a pull request with the fix. When submitting the pull request, please include a detailed description of the bug you are fixing and how your fix addresses the issue.

##### Add Features

If you have an idea for a new feature that you think would be a valuable addition to the project, you can submit a pull request with the new feature. When submitting the pull request, please include a detailed description of the feature and how it will enhance the project.

##### Remove Features

If you think that a feature of the project is unnecessary or problematic, and you have identified a way to remove it without adversely affecting other functionality, you can submit a pull request with the removal. When submitting the pull request, please include a detailed description of the feature you are removing and why you think it should be removed.

##### Refactor

If you think that a portion of the codebase could be improved through refactoring, and you have identified a way to do so without adversely affecting other functionality, you can submit a pull request with the refactor. When submitting the pull request, please include a detailed description of the portion of the codebase you are refactoring and how your changes improve the code.

#### Edit Documentation

Contributions to improve the project's documentation are always welcome. The documentation is an important aspect of the project and helps the users to understand how to use the project, its features and its limitations.

Here are some ways to contribute to the documentation:

* **Fixing typos and grammatical errors**: If you come across any typos or grammatical errors in the documentation, feel free to submit a pull request with the necessary corrections.
* **Adding new content**: If you think that some content is missing from the documentation, you can add it to the documentation by submitting a pull request.
* **Improving existing content**: If you feel that the existing documentation can be improved, you can submit a pull request with the necessary changes.
* **Translating the documentation**: If you are proficient in a language other than English, you can translate the documentation to that language to help non-English speakers to use the project.

Before making any contribution, make sure to read the existing documentation carefully to ensure that your contribution aligns with the existing structure and style.

#### Community Support

Community support is an essential part of any open-source project. You can help support the project by:

* **Answering questions on forums**: If you have expertise in the project or have been using it for some time, you can help answer questions that other users have about the project. This can be done on the project's forum, GitHub issues, or other community forums.
* **Sharing your experience with the project**: If you have been using the project for some time, you can share your experience with the project on social media, blog posts, or other online platforms. This helps to spread the word about the project and attract new users.
* **Mentoring new contributors**: If you have experience contributing to open-source projects, you can help mentor new contributors to the project. This can involve helping them get started with the project, answering their questions, and reviewing their contributions.

#### Donate

Donations are always appreciated and help to support the project's development and maintenance. If you find the project useful, consider making a donation to support its development. You can donate by:

* **One-time donations**: You can make a one-time donation to the project via PayPal, Stripe, or other payment processors.
* **Recurring donations**: You can set up recurring donations to support the project's ongoing development and maintenance.
* **Sponsorship**: If you are a company or organization, you can sponsor the project's development by providing financial support, resources, or other contributions.

All donations will be used to support the project's development and maintenance, such as paying for hosting, domain registration, and development tools.

### Code of Conduct

Contributors shall commit themselves to making the analysis, specification, design, development, testing and maintenance of the project a beneficial and respected responsibility. In accordance with their commitment to the health, safety and welfare of the public, contributors shall adhere to the following Eight Principles:

1. **Public**: Contributors shall act consistently with the public interest.
2. **Project**: Contributors shall act in a manner that is in the best interests of the project consistent with the public interest.
3. **Product**: Contributors shall ensure that their work product and related modifications meet the highest professional standards possible.
4. **Judgement**: Contributors shall maintain integrity and independence in their professional judgment.
5. **Management**: Contribution managers and leaders shall subscribe to and promote an ethical approach to the management of software development and maintenance.
6. **Profession**: Contributors shall advance the integrity and reputation of the profession consistent with the public interest.
7. **Colleagues**: Contributors shall be fair to and supportive of other contributors.
8. **Self**: Contributors shall participate in lifelong learning regarding the practice of their profession and shall promote an ethical approach to the practice of the profession.

## Acknowledgements  

I would like to thank the community for their support and contributions to this project.

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
