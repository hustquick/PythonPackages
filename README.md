This is a module which provides the ability to install the often-used packages written by hustquick.  
To install a package,  
1. Add the package *xxx.py* to the folder _PythonPackages_.
2. Open the file [setup.py](https://github.com/hustquick/PythonPackages/blob/master/setup.py), add the package name 'xxx.py' to the variable "py_modules", then save the file [setup.py](https://github.com/hustquick/PythonPackages/blob/master/setup.py).
3. Open the terminal, the type the command `python3 setup.py install` to finish the install process.
