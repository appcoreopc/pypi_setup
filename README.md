

Setup.py 

Contains setup information require for this simple library. 

README.md

# Test site 
python setup.py register -r pypitest
python setup.py sdist upload -r pypitest

# Live 
python setup.py register -r pypi
python setup.py sdist upload -r pypi

# Place your .pypirc file here 
# With PowerShell (if you are using pew to manage virtualenv for instance),  echo $HOME.
# With default Windows console, echo %HOMEPATH% (yes, talk about "portability")

