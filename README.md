iso-country-codes
=================

## About

This is a Python dictionary of ISO 3166-1 alpha-2 codes and their corresponding country names, as per official ISO site's data in [July 2015](https://web.archive.org/web/20150721184347/http://www.iso.org/iso/home/standards/country_codes/country_names_and_code_elements_txt-temp.htm).

## Usage

```python
>>> from iso_country_codes import CC
>>> len(CC)
249
>>> CC["GR"]
'GREECE'
```
