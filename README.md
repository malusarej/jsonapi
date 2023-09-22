# jsonapi
Assignment 2 for CS5500

# My Project

## Description

My Project is a Python package that extends the json.JSONEncoder and json.JSONDecoder so that complex and range objects can be both serialized and deserialized.

### Coding example
from jsonapi import jsonapi

complex_num = complex(2.0, 3.0)
complex_json = dumps(complex_num)
print("Encoded Complex JSON:", complex_json)

decoded_complex = loads(complex_json) 
print("Decoded Complex Number:", decoded_complex)

#### Installation

You can install My Project using pip:

```shell
pip install -e

