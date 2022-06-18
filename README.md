api-domogeek
============

-->  NO LONGER MAINTAINED <--
A free and simple public API for homeautomation

Old documentation [here](https://domopi.eu/archive/domogeek-lapi-simple-mais-utile/)
__________

I'just fork the project to be resilient at the public api issue.
__________
<br/>
<br/>
<br/>

Install
============

* Pyenv: https://github.com/pyenv/pyenv
* Python 3.10: `pyenv install 3.10.5`
* Make Python 3.10 as default: `pyenv global install 3.10.5`
* Pip dependencies:
  * `python -m pip install redis`
  * `python -m pip install web.py`
  * `python -m pip install urllib2`
  * `python -m pip install urllib`
  * `python -m pip install urllib3`
  * `python -m pip install urlopen`
  * `python -m pip install icalendar`
  * `python -m pip install requests`

Run command
============
* Start: python3.10 apidomogeek.py start
* Stop: python3.10 apidomogeek.py stop
* Restart doesn't work fine anyway