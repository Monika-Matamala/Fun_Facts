# Fun Fact Generator

Welcome to the Fun Fact Generator! This is a web-based application that fetches random fun facts from an external API and displays them to the user. Each time the user clicks the button, a new fun fact is shown.

## Table of Contents
- [Introduction](#introduction)
- [How to Use](#how-to-use)
- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Contribution](#contribution)
- [License](#license)

## Introduction
The Fun Fact Generator is a delightful tool that provides interesting and random fun facts. It uses the `requests` library to fetch data from the [uselessfacts.jsph.pl](https://uselessfacts.jsph.pl) API and `pywebio` to create a user-friendly interface.

## How to Use
1. Run the script to start the web application.
2. Click the "Click me" button to display a fun fact.
3. A new fun fact will appear each time you click the button.

## Features
- Fetches random fun facts from an external API.
- Displays fun facts in a user-friendly format.
- Supports continuous fetching of new facts with a button click.
- Responsive and clear user interface with `pywebio`.

## Requirements
- Python 3.x
- `requests` library
- `pywebio` library

## Setup
1. Ensure you have Python 3.x installed on your system.
2. Install the required libraries using pip:
   ```bash
   pip install requests pywebio
   ```
3. Save the provided script as `fun_fact_generator.py`.
4. Run the script:
   ```bash
   python fun_fact_generator.py
   ```
5. Open the provided local web address in your browser to start using the application.

## Contribution
If you would like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
