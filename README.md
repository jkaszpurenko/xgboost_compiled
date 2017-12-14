# xgboost_compiled
Compiled XGBoost Files for Windows 10
This can be duplicated from the steps in the link below:
https://www.ibm.com/developerworks/community/blogs/jfp/entry/Installing_XGBoost_For_Anaconda_on_Windows?lang=en

I found the instructions to be helpful but thought many people would find it easier to download and install the compiled XGBoost.

If you follow the instructions it is worthwhile to set your install setup of MinGW-W64 to the one shown.  Also change the directory from the default to something like C:\MinGW because MinGW can have trouble with folder names that have spaces in them.  (http://www.mingw.org/wiki/getting_started).

To install in Windows clone this directory.  Open up your prompt.  You can use Anaconda prompt.  And change directories to the cloned folder.  After change directories python-package.  It should look like:

C:\your\path\xgboost\python-package>

Type the following command:
python setup.py install
