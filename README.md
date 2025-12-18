## end to end ml project generic approach
## using setup.py because if anyone wants to use our model it can be used as with packages they dont have to externally install packages it install within project
## now making a function in setup.py get requirements to install anything write in requirements.txt
## create __init__ in src where model is being created because using init it inherits setup .py and we can import packages
## created components pipeline folder in src then exception and logger file in src
## exception for error handling and manipulating, logger for logging outputs, errors
