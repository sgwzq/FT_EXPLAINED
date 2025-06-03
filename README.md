# FT_EXPLAINED
Contains source code for the FT_EXPLAINED web application.
The main Python code is inside "flask_app.py" file.
Web pages are in "templates" directory, and style sheets in "static" directory.
The app needs these requirements:
1. Python 3.7.3 or any version later 
2. Matplotlib 3.1.0 or any version later 
3. Flask 1.0.3 or any version later

## Install with your PC as local host
### First, install python
If you are a Windows user, install python at 
[this](https://www.python.org/downloads/) page.\
**If this is the first time to install python on Windows,
it is recommended to select
`Add python.exe to PATH` at the first installation step**

If Linux, it is recommanded to use distro's package manager.

### Then, install libraries
For Windows users,
first ensure python is in your `Path` Environment Variable,
then you can start `cmd` and run this command:
```sh
pip install numpy scipy matplotlib flask
```
Wait for a moment and all will be done automatically.

For Linux users,
You can install these package using your package manager.

### Finally run the program as a host
Run `flask_app.py` and open the link in the browser ( such as 
`http://127.0.0.1:5000` ) and enjoy!
