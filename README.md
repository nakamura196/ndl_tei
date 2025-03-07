ndl_tei
================

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

## Usage

### Installation

Install latest from the GitHub
[repository](https://github.com/nakamura196/ndl_tei):

``` sh
$ pip install git+https://github.com/nakamura196/ndl_tei.git
```

### Documentation

Documentation can be found hosted on this GitHub
[repository](https://github.com/nakamura196/ndl_tei)’s
[pages](https://nakamura196.github.io/ndl_tei/).

## How to use

``` python
from ndl_tei.core import Client
```

``` python
ndl_xml_path = "./ndl.xml"
output_path = "./ndl.tei.xml"

title = "Sample"

client = Client(ndl_xml_path, title, output_path)
client.convert()
```

    2
