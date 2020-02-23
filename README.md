# README DM CI

![CI test](https://github.com/adjikpo/dm-ci20-4/workflows/CI%20test/badge.svg) ![Php Cs Fixer](https://github.com/adjikpo/dm-ci20-4/workflows/Php%20Cs%20Fixer/badge.svg)

The contribution guide, issue, and pull request templates are given freely that they might be used in other open source projects.
## Contents
- [Usage](#-usage)
- [Requirements](#-requirements)
- [Building your app](#-building-your-app)
- [Documentation](#-documentation)
- [Launch the tests](#-lauch-the-tests)
- [How to Contribute](#-how-to-contribute)
- [License](#-license)
## Usage

Simply copy the `.github` directory to your project, and edit as required.

## 📋 Requirements
🛠Make
🐘PHP >= 7.2
🐳Docker

## 🎉 Building your app

0- If the first utlisation for intall all dependencies

```bash
git clone 
make install_dependencies
```
1- Start the application

```bash
make sart
```

## 📖 Documentation


## ⚙️ Launch the tests

1- Launching all test

```bash
make all_tests
```

2- Launching of the 3 tests separately

    2.1 Unit
    ```bash
    make all_tests
    ```

    2.1 Integration
    ```bash
    make test_integration
    ```

    2.1 Funtional
    ```bash
    make test_functional
    ```

## 👏 How to Contribute [contribute]

The main purpose of this repository is to continue evolving DM CI core. We want to make contributing to this project as easy and transparent as possible, and we are grateful to the community for contributing bug fixes and improvements. Read below to learn how you can take part in improving DM CI.
Please read [**Contributing.md**][contribute] to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to DM CI.

[contribute]: https://github.com/adjikpo/dm-ci20-4/docs/contributing

### [Contributing Guide][contribute]


## 📄 License

DM CI is MIT licensed, as found in the [LICENSE][l] file.

DM CI documentation is Creative Commons licensed, as found in the [LICENSE-docs][ld] file.

[l]: https://github.com/adjikpo/dm-ci20-4
[ld]: https://github.com/adjikpo/dm-ci20-4