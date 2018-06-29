# python-libraries

## Status

[![Download](https://api.bintray.com/packages/geldtech/debian/python-libraries/images/download.svg)](https://bintray.com/geldtech/debian/python-libraries#files)
[![Build Status](https://travis-ci.org/geld-tech/python-libraries.svg?branch=master)](https://travis-ci.org/geld-tech/python-libraries)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


## Description

Python libraries centralised to ease deployment and re-use


## Usage

* Install the repository information and associated GPG key (to ensure authenticity):
```
$ echo "deb https://dl.bintray.com/geldtech/debian /" | sudo tee -a /etc/apt/sources.list.d/geld-tech.list
$ sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com EA3E6BAEB37CF5E4
```

* Update repository list of available packages and clean already installed versions
```
$ sudo apt update
$ sudo apt clean
```

* Install package
```
$ sudo apt install python-libraries
```

* Import and use in Python code
```
>>> import sys
>>> sys.path.append('/opt/geld/libs/python')
>>> 
>>> from oauth2 import *
>>> from nginxparser import *
>>> from screenshot import *
```


