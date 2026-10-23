# Interest Calculator CLI

<p align="center">
  <img src="assets/interest-calculator-mark.svg" alt="Interest Calculator logo" width="120">
</p>

<p align="center">
  A fast, lightweight Bash CLI for calculating simple interest and final amounts.
</p>

<p align="center">
  <a href="https://github.com/PVegananda/github-final-project/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-2ea44f?style=flat-square" alt="Apache 2.0 license"></a>
  <img src="https://img.shields.io/badge/shell-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Linux-555?style=flat-square" alt="macOS and Linux">
</p>

## Overview

Interest Calculator is a focused Bash utility for quickly working out simple
interest from a principal amount, annual interest rate, and time period. It
keeps the interaction clear, validates user input, and presents both the
calculated interest and the final amount in a readable format.

The calculation uses the standard formula:

```text
Simple Interest = (Principal × Rate × Time) / 100
Final Amount = Principal + Simple Interest
```

## Features

- Simple, interactive command-line workflow
- Input validation for principal, rate, and time
- Two-decimal financial calculations using `bc`
- Clear output for the interest earned and final amount
- No external runtime or application framework required

## Requirements

- Bash 3.2 or later
- `bc`
- macOS or Linux

## Getting started

Clone the repository and enter its directory:

```bash
git clone https://github.com/PVegananda/interest-calculator-cli.git
cd interest-calculator-cli
```

Make the script executable:

```bash
chmod +x interest-calculator.sh
```

Run the calculator:

```bash
./interest-calculator.sh
```

Enter the principal amount, annual interest rate, and time period in years
when prompted.

## Project structure

```text
interest-calculator.sh  Interactive calculator
assets/                 Project branding assets
```

## Contributing

Suggestions and improvements are welcome. Please read
[CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or pull request.

## License

This project is available under the Apache License 2.0. See [LICENSE](LICENSE)
for the full license text.

## Author

Built and maintained by [PVegananda](https://github.com/PVegananda).
