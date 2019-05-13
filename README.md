# Deprecation Notice


> This module has been deprecated and is now replaced with the https://github.com/ThreatConnect-Inc/tcex module. For working with the ThreatConnect REST API see the docs on the TcEx TI (Threat Intelligence) module (https://threatconnect-inc.github.io/tcex/module_ti.html). For Apps written outside of ThreatConnect Exchange see the section on External App Templates (https://threatconnect-inc.github.io/tcex/building_apps_tcinit.html#external-app-templates).

The threatconnect-python project is a part of the ThreatConnect&trade; SDK.
This module implement methods that can be used to push or pull data from the [ThreatConnect V2 REST API](https://docs.threatconnect.com/en/latest/rest_api/rest_api.html).

# threatconnect-python

## Requirements

The threatconnect-python project can run under Python 2.7 and 3.4+.

All python versions:
 * requests 2.7+ module (http://docs.python-requests.org/en/latest/).
 * python-dateutil module (https://pypi.python.org/pypi/python-dateutil).

Python 2 requirements:
 * enum34 module (https://pypi.python.org/pypi/enum34).

API credentials with a ThreatConnect instance are required to run this module.
Please see https://www.threatconnect.com/products/ for more information on ThreatConnect versions.

## Installation

```sh
cd threatconnect-python
python setup.py install --force
```

Using pip
```sh
pip install threatconnect
```

## Documentation

https://docs.threatconnect.com/en/latest/python/python_sdk.html

## Examples

https://github.com/ThreatConnect-Inc/threatconnect-python/tree/master/examples

## Contact

If you have any questions, bugs, or requests please contact support@threatconnect.com
