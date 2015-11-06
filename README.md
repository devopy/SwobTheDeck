# Environment Canada SWOB-ML Parser

Parses SWOB-ML information from http://dd.weather.gc.ca/observations/swob-ml/

## Installation Instructions

 * On Ubuntu 14.04
  * Install pip and virtualenv:
    ```
    sudo apt-get install python-pip python-dev build-essential
    sudo pip install --upgrade pip
    sudo pip install --upgrade virtualenv
    ```
  * Create a virtualenv
    ```
    virtualenv envcan
    ```
  * Activate virtualenv
    ```
    source envcan/bin/activate
    ```
  * Install packages
    ```
    pip install -r REQUIREMENTS.txt
    ```
  * Read the code.  See the examples at the bottom
  * Run the code:
    ```
    python parser.py
    ```
  * Later you can deactivate the virtualenv
    ```
    deactivate
    ```
  * The necessary packages are installed in the virtualenv, so the envcan virtualenv must be active so that the code works.

## Changes

More changes are coming soon, including more comprehensive documentation and support for Python 3.

**Coming soon:**
 * Python 3 Support
 * Generate HTML tables
 * Support for cache
 * Improved multi station support
