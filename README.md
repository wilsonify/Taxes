# Taxes

Tax Computation

This project provides tools for calculating taxes. It includes functions for calculating federal, state, and local taxes, as well as a class for storing and manipulating tax data.
Requirements

    Python 3.6 or later

Installation

To install the package, use pip:

pip install tax-computation

Usage

Here is an example of how to use the package to calculate federal taxes:

from tax_computation import federal_tax

taxable_income = 50000
filing_status = 'single'

tax = federal_tax(taxable_income, filing_status)
print(tax)

The package also includes a TaxData class for storing and manipulating tax data. Here is an example of how to use it:

from tax_computation import TaxData

data = TaxData(taxable_income=50000, filing_status='single')
data.calculate_federal_tax()
print(data.federal_tax)

Contributing

We welcome contributions to the project. If you would like to contribute, please follow these guidelines:

    Fork the repository
    Create a new branch for your changes
    Make your changes
    Run the tests to ensure that everything is working correctly
    Commit your changes and push them to your fork
    Submit a pull request for your changes to be reviewed and merged

License

This project is licensed under the MIT License.
