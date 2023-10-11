# noroot_ping
Simple python bindings to rust's tokio tcp ping function. This package is intended to be a leight weight solution for tcp pings
without needing root on linux based systems.

## Installation
```
pip install noroot_ping
```

## Usage
```
from noroot_ping import ping_tcp

if ping_tcp(ip, port):
    # if ping was successful
else:
    # if ping was NOT successful
```
