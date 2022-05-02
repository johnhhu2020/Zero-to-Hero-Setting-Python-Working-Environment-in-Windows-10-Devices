# Zero-to-Hero-Setting-Python-Working-Environment-in-Windows-10-Devices




Microsoft Windows [Version 10.0.17763.2867]
(c) 2018 Microsoft Corporation. All rights reserved.

C:\Users\JJ>mkdir python310

C:\Users\JJ>cd python310

C:\Users\JJ\python310>py get-pip.py
C:\Users\JJ\AppData\Local\Programs\Python\Python310\python.exe: can't open file 'C:\\Users\\JJ\\python310\\get-pip.py': [Errno 2] No such file or directory

C:\Users\JJ\python310>py -m ensurepip --upgrade
Looking in links: c:\Users\JJ\AppData\Local\Temp\tmp_ic7erow
Requirement already satisfied: setuptools in c:\users\jj\appdata\local\programs\python\python310\lib\site-packages (58.1.0)
Requirement already satisfied: pip in c:\users\jj\appdata\local\programs\python\python310\lib\site-packages (22.0.4)

C:\Users\JJ\python310>pip --version
pip 22.0.4 from C:\Users\JJ\AppData\Local\Programs\Python\Python310\lib\site-packages\pip (python 3.10)

C:\Users\JJ\python310>pip install virtualenv
Collecting virtualenv
  Using cached virtualenv-20.14.1-py2.py3-none-any.whl (8.8 MB)
Collecting platformdirs<3,>=2
  Using cached platformdirs-2.5.2-py3-none-any.whl (14 kB)
Collecting distlib<1,>=0.3.1
  Using cached distlib-0.3.4-py2.py3-none-any.whl (461 kB)
Collecting six<2,>=1.9.0
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Collecting filelock<4,>=3.2
  Using cached filelock-3.6.0-py3-none-any.whl (10.0 kB)
Installing collected packages: distlib, six, platformdirs, filelock, virtualenv
Successfully installed distlib-0.3.4 filelock-3.6.0 platformdirs-2.5.2 six-1.16.0 virtualenv-20.14.1

C:\Users\JJ\python310>virtualenv venv
created virtual environment CPython3.10.4.final.0-64 in 4096ms
  creator CPython3Windows(dest=C:\Users\JJ\python310\venv, clear=False, no_vcs_ignore=False, global=False)
  seeder FromAppData(download=False, pip=bundle, setuptools=bundle, wheel=bundle, via=copy, app_data_dir=C:\Users\JJ\AppData\Local\pypa\virtualenv)
    added seed packages: pip==22.0.4, setuptools==62.1.0, wheel==0.37.1
  activators BashActivator,BatchActivator,FishActivator,NushellActivator,PowerShellActivator,PythonActivator

C:\Users\JJ\python310>.\venv\Scripts\activate

(venv) C:\Users\JJ\python310>pip list
Package    Version
---------- -------
pip        22.0.4
setuptools 62.1.0
wheel      0.37.1

(venv) C:\Users\JJ\python310>pip install C:/Users/JJ/Downloads/numpy-1.22.3+mkl-cp310-cp310-win_amd64.whl
Processing c:\users\jj\downloads\numpy-1.22.3+mkl-cp310-cp310-win_amd64.whl
Installing collected packages: numpy
Successfully installed numpy-1.22.3+mkl


(venv) C:\Users\JJ\python310>pip install C:/Users/JJ/Downloads/jupyterlab-3.3.4-py3-none-any.whl

(venv) C:\Users\JJ\python310>


C:\Users\JJ\Downloads\numpy-1.22.3+mkl-cp310-cp310-win_amd64.whl
