Python Apple Support
====================

This is a meta-package for building a version of Python that can be embedded
into a macOS, iOS, tvOS or watchOS project.

It works by downloading, patching, and building a fat binary of Python and
selected pre-requisites, and packaging them as static libraries that can be
included in an Xcode project.

The binaries support x86_64 for macOS; arm64 for Python 3.8+; arm64 for iOS
and appleTV devices; and armv7k for watchOS. This should enable the code to
run on:

* MacBook (including MacBooks using Apple Silicon)
* iMac (including iMacs using Apple Silicon)
* Mac Mini (including Mac Minis using Apple Silicon)
* Mac Pro
* iPhone (5s or later)
* iPad (5th gen or later)
* iPad Air (all models)
* iPad Mini (2 or later)
* iPad Pro (all models)
* iPod Touch (6th gen or later)
* Apple TV (4th gen or later)
* Apple Watch

The master branch of this repository has no content; there is an
independent branch for each supported version of Python. The following
Python versions are supported:

* `Python 3.7 <https://github.com/beeware/Python-Apple-support/tree/3.7>`__
* `Python 3.8 <https://github.com/beeware/Python-Apple-support/tree/3.8>`__
* `Python 3.9 <https://github.com/beeware/Python-Apple-support/tree/3.9>`__
* `Python 3.10 <https://github.com/beeware/Python-Apple-support/tree/3.10>`__
* `Python 3.11 <https://github.com/beeware/Python-Apple-support/tree/3.11>`__

Suggestions for changes should be made against the `dev branch
<https://github.com/beeware/Python-Apple-support/tree/dev>`__; these
will then be backported into the supported Python releases. The dev branch will
track the most recent supported version of Python (currently, Python 3.11).

See the individual branches for usage instructions.

The following versions were supported in the past, but are no longer
maintained:

* `Python 2.7 <https://github.com/beeware/Python-Apple-support/tree/2.7>`__ (EOL January 2020)
* `Python 3.4 <https://github.com/beeware/Python-Apple-support/tree/3.4>`__ (EOL March 2019)
* `Python 3.5 <https://github.com/beeware/Python-Apple-support/tree/3.5>`__ (EOL February 2021)
* `Python 3.6 <https://github.com/beeware/Python-Apple-support/tree/3.6>`__ (EOL December 2021)
