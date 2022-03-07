# Example of how to use Google-Earth-Engine-API with Python 
This repo contains some examples of how to use the Google-Earth-Engine-API (GEE-API) with a pipenv python environment. 

## Usage 
You can clone this repo in a terminal by typing (your destination should match where your .pipenv and .pyenv are installed. For me, that in \NSh.)

        C:\Users\SuI\Documents\code\>git clone https://ngi001@dev.azure.com/ngi001/NGI/_git/google-earth-engine-API-example

Change into the new directory 

        C:\Users\SuI\Documents\code\> cd google-earth-engine-API-example     

and start a virtual environment from the command line 

        C:\Users\SuI\Documents\code\google-earth-engine-API-example> pipenv shell 
        Launching subshell in virtual environment...
        Microsoft Windows [Version 10.0.19043.1526]
        (c) Microsoft Corporation. All rights reserved.

If instead you get an error message "'pipenv is not recognized...", try typing 'python m- pipenv shell'

First time you use the code in this repo you need to install the dependencies of the virtual environment (note, the string in parentheses indicates you are within a virtual environment)

        (google-earth-engine-API-example-jOx4Q0kO-shims) C:\Users\SuI\Documents\code\google-earth-engine-API-example> pipenv install 

see notes below about error messages

Then you can either run the [notebook through VSC](https://code.visualstudio.com/learn/educators/notebooks) or through your browser by the command 

        (google-earth-engine-API-example-jOx4Q0kO-shims) C:\Users\SuI\Documents\code\google-earth-engine-API-example> jupyter-lab     

(See notes below about attempt to open in VSC)
(After that effort dead ended, I tried the browser option. Seemed like a better start but still did not know how to run the hello_world file, for example...)

### Tips 
Some other examples of how to use the API with [python scripts](https://github.com/google/earthengine-api/tree/master/python/examples/py) and [jupyter notebooks](https://github.com/google/earthengine-api/tree/master/python/examples/ipynb). 

## Dependencies
To run the code in this repo you need to have installed 
- pyenv, [NGI-adapted guide](https://ngiwiki.slite.com/app/docs/KXWBnnQrSS_Uu4)
- pipenv, [NGI-adapted guide](https://ngiwiki.slite.com/app/docs/tO10k0gX_U-6Ve)


The code in this repo has been succsessfully ran on: 
- WSL, Ubuntu 20.04 
- cmd Windows 10 

 ### Notes from my first try:
when installing the dependencies, I got 2 error messages though it otherwise appeared succsessfully
1. Ignoring pexpect: markers 'sys_platform != "win32"' don't match your environment
2. Ignoring ptyprocess: markers 'os_name != "nt"' don't match your environment

### Steps to open example in Visual Studio (that didn't end up working)
1. open VS
2. select 'open folder'
3. navigate to location of the cloned repository
4. open the .virtualenvs folder
5. select google earth engine example and click 'select folder'
6. actually, this seemed to be a dead end. I couldn't find a sample file or jupyter notebook to run in VS. went back to cmd and ran on browser.