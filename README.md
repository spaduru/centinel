### Centinel

Centinel is a tool used to detect network interference and internet
censorship.

#### Install and usage
##### Debian
    $ sudo apt-get install python-pip libssl-dev swig python-dev libffi-dev tcpdump libcurl4-openssl-dev traceroute
    $ sudo pip install -U pip
    $ sudo pip install centinel
    $ centinel

##### OSX
    $ sudo pip install centinel
    $ centinel

##### Latest development version
    * git clone https://github.com/iclab/centinel.git
    # install dnspython, requests
    * sudo python setup.py install
    * python centinel.py

#### Supported platforms

    * Linux/OS X
    * BISmark Routers
    * Android
