Important Installation for development purpose (Temporal)
---------------------------------------------------------
Stackops python-automationclient is under development taking as groundwork the project
Openstack python-cinderclient, therefore to recreate the current project you need to clone this one
throught the command ``git clone https://github.com/StackOps/python-automationclient`` and then follow the
next steps:

1. Go to the directory ``python-automationclient``
2. Once on the directory run the command ``python tools/install_venv.py`` to create a virtual environment
   to work on it
3. Activate the virtual environment with the command ``source .venv/bin/activate``
4. Install the python-automationclient throught the command ``python setup.py install``
5. This is all!! Start to contribute....
