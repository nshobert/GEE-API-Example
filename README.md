# Example of how to use Google-Earth-Engine-API with Python 
This repo contains some examples of how to use the Google-Earth-Engine-API (GEE-API) with a pipenv python environment. 

## Usage 
You can clone this repo in a terminal by typing

        C:\Users\<USERNAME>> git clone https://github.com/nshobert/GEE-API-Example.git

Change into the new directory 

        C:\Users\<USERNAME>> cd google-earth-engine-API-example     

and start a virtual environment from the command line 

        C:\Users\<USERNAME>\google-earth-engine-API-example> pipenv shell 
        Launching subshell in virtual environment...
        Microsoft Windows [Version 10.0.19043.1526]
        (c) Microsoft Corporation. All rights reserved.

If instead you get an error message "'pipenv is not recognized...", try instead the command `python -m pipenv shell`

First time you use the code in this repo you need to install the dependencies of the virtual environment (note, the string in parentheses indicates you are within a virtual environment)

        (google-earth-engine-API-example-jOx4Q0kO-shims) C:\Users\<USERNAME>\google-earth-engine-API-example> pipenv install 

Error messages such as the following can be ignored:
1. Ignoring pexpect: markers 'sys_platform != "win32"' don't match your environment
2. Ignoring ptyprocess: markers 'os_name != "nt"' don't match your environment

Then you can either run the notebook on a browser by using the following terminal command or run the [notebook through VSC](https://code.visualstudio.com/learn/educators/notebooks).

        (google-earth-engine-API-example-jOx4Q0kO-shims) C:\Users\<USERNAME>\google-earth-engine-API-example> jupyter-lab     

### Tips 
- Another repo contains a thorough tutorial of the geemap package, a valuable package for adding visualization functionality the GEE Python API. Strongly recommneded to work through it!
- Some other examples of how to use the API with [python scripts](https://github.com/google/earthengine-api/tree/master/python/examples/py) and [jupyter notebooks](https://github.com/google/earthengine-api/tree/master/python/examples/ipynb). 

## Dependencies
To run the code in this repo you need to have installed 
- pyenv
- pipenv


The code in this repo has been succsessfully ran on: 
- WSL, Ubuntu 20.04 
- cmd Windows 10 
