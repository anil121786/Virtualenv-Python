# Virtualenv-Python

By this time, make sure that you installed the python already.

Steps to install and setup virtualenv:

1. First of all, install pip: `sudo apt-get install python3-pip`

2. Install virtualenv using pip3: `sudo pip3 install virtualenv` 
3. Create a virtual environment: `virtualenv venv` 
    
    You can use any name instead of venv
    
    You can also use a Python interpreter of your choice: `virtualenv -p /usr/bin/python2.7 venv`

4. Activate your virtual environment: 

    `source venv/bin/activate`

    Using fish shell: `source venv/bin/activate.fish`

    To deactivate: `deactivate`

    

### Create virtualenv using Python3

`virtualenv -p python3 myenv`

Instead of using virtualenv you can use this command in Python3: `python3 -m venv myenv`
