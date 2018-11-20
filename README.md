![alt tag](/docs/source/_static/dsp3_logo3.png?raw=true "DSP3")

DSP3-Python2
====
[![Build Status](https://travis-ci.org/jeffthorne/DSP3.svg?branch=master)](https://travis-ci.org/jeffthorne/deep_security)

A Python 2 compatible SDK for Trend Micro's Deep Security platform. Back-ported from Python 3 library: https://github.com/jeffthorne/DSP3

## Python 2 Library Requirements
certifi (https://pypi.org/project/certifi/)
chardet (https://pypi.org/project/chardet/)
idna (https://pypi.org/project/idna/)
pytz  (https://pypi.org/project/pytz/)
requests (https://github.com/requests/requests)
suds (https://pypi.org/project/suds/)
urllib3 (https://pypi.org/project/urllib3)
six (https://pypi.org/project/six/)
typing (https://pypi.org/project/typing/)

## Installation
Manual source extraction


## Documentation
http://dsp3.readthedocs.io

## Examples

To run use cases from project dir as an example: python -m examples.alerts<br/>

1.  Authentication: [examples/authentication.py](examples/authentication.py)
2.  Get events: [examples/get_events.py](examples/get_events.py)
3.  Create block by file hash rules: [examples/block_by_hash.py](examples/block_by_hash.py)
4.  Get manager info: [examples/manager_info.py](examples/manager_info.py)
5.  Alerts: [examples/alerts.py](examples/alerts.py)
6.  Host/s operations: [examples/host.py](examples/host.py)
7.  Administrators: [examples/administrators.py](examples/administrators.py)
8.  Event based tasks: [examples/event_based.py](examples/event_based.py)
9.  Relays: [examples/relays.py](examples/relays.py)
10. Scripts: [examples/scripts.py](examples/scripts.py)
11. Reports: [examples/reports.py](examples/reports.py)

## Use Cases
The following examples are some use cases seen in the field.<br/>
To run use cases from project dir: python -m usecases.eventscsv

1. Retrieve events to csv files: [usecases/eventscsv.py](usecases/eventscsv.py)
