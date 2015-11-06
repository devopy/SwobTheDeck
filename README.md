# Parser for SWOB-ML files from Environment Canada's MSC

Parses SWOB-ML information from http://dd.weather.gc.ca/observations/swob-ml/

See source code in ```parser.py```.

## Installation Instructions

 * On Ubuntu 14.04
  * Download or clone the repository:
    * Use the 'Download ZIP' button on the right OR
    * ```git clone https://github.com/devopy/SwobTheDeck.git``` or ```git clone git@github.com:devopy/SwobTheDeck.git```
    
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
  * Read the code.  See the examples at the bottom of ```parser.py```.
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
