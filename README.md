# PyDD Commons

PyDD are preconfigured components that helps you to build microservices in python. PyDD Commons offers basic microservice functionalities so you do not need to start everything from scratch. This modules preconfigures:

* Configuration
* Logging

## Installing

Install using pip:

```pip install pyddcommons```

## A Simple Example

```python
from pyddcommons import pydd_commons

pydd_commons(config_mapping, modules_init_functions=[
    # list additional modules
])
```

