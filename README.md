# Billing Generator
> The script reads, transforms and loads information from dataframe into unique PDF files to generate a detailed bill-form document.

The following diagram douments the process run by the script to generate the final bill.
<img src="billing_generator.png" height="10%" width="25%" style = "display: block;margin-left: auto;margin-right: auto;width: 100%;margin:10px">

![](header.png)

## Usage example

The script generates a bill document per row in the table. Sample of the billing design.
<img src="example_billing.png" height="25%" width="10%" style = "display: block;margin-left: auto;margin-right: auto;width: 50%;">


## Development setup

Main libraries in main script:

1. [![pandas][python-pandas-badge]][python-pandas-url], for data transformation
2. [![psycopg2][python-psycopg2-badge]][python-psycopg2-url], for connecting with PostgresSQL
3. [![base64][python-base64-badge]][python-base64-url], for designing the PDF

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[python-pandas-badge]: https://img.shields.io/badge/python-pandas-blue
[python-pandas-url]: https://pypi.org/project/pandas/
[python-psycopg2-badge]:https://img.shields.io/badge/python-psycopg2-green
[python-psycopg2-url]: https://pypi.org/project/psycopg/
[python-base64-badge]: https://img.shields.io/badge/python-base64-yellow
[python-base64-url]: https://pypi.org/project/pybase64/

