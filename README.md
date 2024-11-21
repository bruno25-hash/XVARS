XVARS-TOOL has been originated from the Variogram Analysis of Response Surface (VARS) method of sensitivity analysis to be used with the prediction results of the machine learning (ML) models.

XVARS-TOOL runs a sensitivity analysis when the theoretical distribution of some inputs is unknown or too complex. 
Here, the G-VARS (By Do and razavi, 2020) is further extended to accommodate any complex distribution of data that are often encountered with environmental systems studies.",

The code provided for application of XVARS has been included in the current repository.
Before implementing the XVARS-TOOL with the ML models, the VARS-TOOl needs to be installed in your computer.


#VARS-TOOL Installation
1. Installing with pip (preferred)
If you have Python3 and pip installed on your machine, then the VARS-TOOL package can be installed as following:
foo@bar:~$ pip install varstool

2. Installing from source code
To install the lastest VARS-TOOL code from the source code, you will need to clone the github repository onto your local device using the command:
foo@bar:~$ git clone https://github.com/vars-tool/vars-tool.git
To install the package, enter the VARS-TOOL directory and run:

foo@bar:~$ cd vars-tool
foo@bar:~$ pip install .
If pip is not available on your device use:

foo@bar:~$ python setup.py install
☝️	If installation does not work due to limited permissions, add the --user option to the install commands.
If you do not have anaconda or git installed, there is a guide on how to install them located here


#The following github repository provides the details into the VARS-TOOL toolbox installation and theory.
https://github.com/vars-tool/vars-tool.git
