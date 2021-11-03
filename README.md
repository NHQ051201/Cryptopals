# Cryptopals 

This are my solutions.

The code is written in pure Python 3 and it is extensively documented.

## How to run

I recommend using a Python virtual environment. Here is a very small cheat sheet for it:

```sh
# Install virtualenv if not already installed
$ pip3 install virtualenv

# Create the virtual environment
$ virtualenv -p python3 venv

# Activate the virtual environment
$ source venv/bin/activate

# Install the dependencies
$ pip3 install requests 
$ pip3 install flask 
$ pip3 install pycrypto

# Deactivate the environment (after you are done running the challenges):
$ deactivate
```

When the environment is ready, you can run each challenge by simply calling `python S*C**.py`, after 
 replacing `*` with the number of the set, and `**` with the number of the challenge. Beware that:
 - Some challenges take a long time to run.
 - For some challenges you might need to run the server first.
