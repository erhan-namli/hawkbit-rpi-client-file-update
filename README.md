# hawkbit-rpi-client-file-update
This repository includes instructions about updating files on our target raspberry pi client device from the hawkbit server.

## Instructions

- Firstly be sure about your hawkbit server setup
- Then install the rpi-hawkbit-client from gitlab
- Install the required python libraries, such as docker, note that you have to install the docker with pip3 not with pip
- This repository installs the hbloader into your system via setup.py sdist, note that `python3 setup.py sdist` 
- And the correction of second installation command of hbloader is `pip3 install --user dist/hbloader-1.0.0.tar.gz`
- `export PATH=$PATH:$HOME/.local/bin`
- Then the installation is done, you can run the hbloader with this command `hbloader.py`


## Resources

- https://gitlab.com/iamp/rpi-hawkbit-client
