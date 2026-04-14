# PythonCLI

## Overview

`PythonCLI` is a collection of simple command-line utilities written in Python, including tools for Base64 encoding/decoding and basic system information.

## Usage

### Base64 utility (`b64`)

Encode a string:

`python b64 -e "your string"`

Decode a string:

`python b64 -d "encoded_string"`

### CPU info utility (`cpuinfo`)

Show CPU core count:

`python cpuinfo -c`

Show load average:

`python cpuinfo -l`

## Requirements

- Python 3.x
- psutil
