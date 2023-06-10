[![Build Status](https://travis-ci.org/firebase/firebase-admin-python.svg?branch=master)](https://travis-ci.org/firebase/firebase-admin-python)
[![Python](https://img.shields.io/pypi/pyversions/firebase-admin.svg)](https://pypi.org/project/firebase-admin/)
[![Version](https://img.shields.io/pypi/v/firebase-admin.svg)](https://pypi.org/project/firebase-admin/)
# Time Skew issue:
Now you can pass click_skew (in seconds) to verify_id_token method when verify id token to take in account 
the time skew between Firebase time and server time.
```python
decoded_token = auth.verify_id_token(id_token, clock_skew=60) # 60 sec
```
# Firebase Admin Python SDK

## Table of Contents

 * [Overview](#overview)
 * [Installation](#installation)
 * [Contributing](#contributing)
 * [Supported Python Versions](#supported-python-versions)
 * [Documentation](#documentation)
 * [License and Terms](#license-and-terms)

## Overview

[Firebase](https://firebase.google.com) provides the tools and infrastructure
you need to develop apps, grow your user base, and earn money. The Firebase
Admin Python SDK enables access to Firebase services from privileged environments
(such as servers or cloud) in Python. Currently this SDK provides
Firebase custom authentication support.

For more information, visit the
[Firebase Admin SDK setup guide](https://firebase.google.com/docs/admin/setup/).


## Installation

To install Firebase Admin Python SDK, simply execute the following command
in a terminal:

```
pip install firebase-admin
```

## Contributing

Please refer to the [CONTRIBUTING page](./CONTRIBUTING.md) for more information
about how you can contribute to this project. We welcome bug reports, feature
requests, code review feedback, and also pull requests.


## Supported Python Versions

We currently support Python 3.7+. Firebase
Admin Python SDK is also tested on PyPy and
[Google App Engine](https://cloud.google.com/appengine/) environments.


## Documentation

* [Setup Guide](https://firebase.google.com/docs/admin/setup/)
* [API Reference](https://firebase.google.com/docs/reference/admin/python/)


## License and Terms

Firebase Admin Python SDK is licensed under the
[Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

Your use of Firebase is governed by the
[Terms of Service for Firebase Services](https://firebase.google.com/terms/).
