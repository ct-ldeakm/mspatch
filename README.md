# MSPATCH
MSPATCH is simple, low dependency, service that reports "Windows Update" results to cloud based blob storage. 
## Features
1. Windows Installer x86 & x64
1. Compressed posted payloads
1. Data of last "Windows Update" scan results

## Security
Unlike other tools of this nature. MSPATCH requires only the security right needed to preform a Windows Update scan.

## Configuration Options
1. Destination bucket (GCP only) ATM
1. HTTP Proxy for outbound report HTTP POST requests

## Service Design Document
https://docs.google.com/document/d/1wPW95FD69rzcDKDUh0pBLv6Hl_WeHgeC0-nsmivIVj4/edit
