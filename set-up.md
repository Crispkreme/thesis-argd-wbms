## Set-up

WARNING: Running pip as the 'root' user can result in broken permissions and conflicting behaviour with the system package manager. It is recommended to use a virtual environment instead: https://pip.pypa.io/warnings/venv

**Solution**
- pip3 install virtualenv
- cd /path/to/your/project
- virtualenv -p python3 venv
- source venv/bin/activate
- pip3 install Adafruit_DHT
- deactivate
