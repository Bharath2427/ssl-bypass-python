# ssl-bypass-python
Process to bypass ssl and install python libraries
step 1 - go to run
%APPDATA%\ - search
Create a file by the name pip and inside that create a ini file (initially to be .txt file then remove ,txt from it.
Then put this there.
[global]
trusted-host = pypi.python.org
               pypi.org
               files.pythonhosted.org
Save and close
 
step 2 - go to pycharm - files - settings - python interpreter - + symbol (then install below packages)
- install numby
- install pandas
