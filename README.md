# Loan Qualifier

This project uses a csv file of bank information as well as user information such as credit score, debt, income, loan amount and home value to determine which bank loans are available to them and optionally create a csv file of the qualified loans

---

## Technologies

This program utilizes Python as well as the following dependencies:

* [fire](https://github.com/google/python-fire) - For the command line interface and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs.

---

## Installation Guide

Before running the code, the following dependencies must be installed:

```python
pip install fire
pip install questionary
```

---

## Usage

To use this application, simply clone the repository and run **app.py**

```python
python app.py
```

The user will be prompted to enter the path for the bank data as well as their credit score, debt, income, loan amount and home value.

If there are available loans, the user will be asked if they want to save the data as a csv and will be prompted input a path to save to.

---

## Contributors

Brought to you by Majid Kouki. You can reach me at [majidkpy@gmail.com](mailto:majidkpy@gmail.com).

---

## License

MIT
