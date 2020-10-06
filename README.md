# Simple-Network-Scanner
A simple network scanner that sends ping probes to check if a device is up on a network and which ports are working.

# Usage

usage: python3 NetScan.py [-h] [-p PORT [PORT ...]] [-sp] [-v] [-f] Host [Host ...]

Checks if a Host is up or not

positional arguments:
  Host                  Host URL/IP Address.

optional arguments:
  -h, --help            show this help message and exit
  -p PORT [PORT ...], --port PORT [PORT ...]
                        Port number(s) to scan.
  -sp, --PingScan       Only check if host is/are up.
  -v, --verbose         Verbose mode.
  -f, --force           Assume that the host is up.
