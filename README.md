# python_hcl2
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/dbdef52c39fb47c896aa1d7876a3a965)](https://www.codacy.com?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=amplify-education/python_hcl2&amp;utm_campaign=Badge_Grade)
[![Codacy Badge](https://api.codacy.com/project/badge/Coverage/dbdef52c39fb47c896aa1d7876a3a965)](https://www.codacy.com?utm_source=github.com&utm_medium=referral&utm_content=amplify-education/python_hcl2&utm_campaign=Badge_Coverage)
[![Build Status](https://travis-ci.org/amplify-education/python_hcl2.svg?branch=master)](https://travis-ci.org/amplify-education/python_hcl2)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/amplify-education/python_hcl2/master/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/python_hcl2.svg)](https://pypi.org/project/python_hcl2/)
[![Python Versions](https://img.shields.io/pypi/pyversions/python_hcl2.svg)](https://pypi.python.org/pypi/python_hcl2)
[![Downloads](https://img.shields.io/badge/dynamic/json.svg?label=downloads&url=https%3A%2F%2Fpypistats.org%2Fapi%2Fpackages%2Fpython_hcl2%2Frecent&query=data.last_month&colorB=brightgreen&suffix=%2FMonth)](https://pypistats.org/packages/python_hcl2)

A parser for [HCL2](https://github.com/hashicorp/hcl2/blob/master/hcl/spec.md) written in Python using 
[Lark](https://github.com/lark-parser/lark).  

## About Amplify

Amplify builds innovative and compelling digital educational products that empower teachers and students across the 
country. We have a long history as the leading innovator in K-12 education - and have been described as the best tech 
company in education and the best education company in tech. While others try to shrink the learning experience into  
the technology, we use technology to expand what is possible in real classrooms with real students and teachers.

Learn more at <https://www.amplify.com>

## Getting Started
### Prerequisites

python_hcl2 requires Python 3.6.0 or higher to run.

### Installing

This package can be installed using `pip`

```sh
pip3 install python_hcl2
```

### Usage
```python
import hcl2
with(open('foo.tf', 'r')) as file:
    dict = hcl2.load(file)
```

## Building From Source

For development, `tox>=2.9.1` is recommended.

### Running Tests

python_hcl2 uses `tox`. You will need to install tox with `pip install tox`.
Running `tox` will automatically execute linters as well as the unit tests.

You can also run them individually with the `-e` argument.

For example, `tox -e py37-unit` will run the unit tests for python 3.7

To see all the available options, run `tox -l`.

## Responsible Disclosure
If you have any security issue to report, contact project maintainers privately.
You can reach us at <mailto:github@amplify.com>

## Contributing
We welcome pull requests! For your pull request to be accepted smoothly, we suggest that you:
1. For any sizable change, first open a GitHub issue to discuss your idea.
2. Create a pull request.  Explain why you want to make the change and what it’s for.
We’ll try to answer any PR’s promptly.