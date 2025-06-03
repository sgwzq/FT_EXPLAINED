# FT_EXPLAINED
Contains source code for the FT_EXPLAINED web application.
The main Python code is inside "flask_app.py" file.
Web pages are in "templates" directory, and style sheets in "static" directory.
The app needs these requirements:
1. [Python](https://www.python.org)
2. [Matplotlib](https://matplotlib.org)
3. [Numpy](https://numpy.org)
4. [Scipy](https://scipy.org)
5. [Flask](https://flask.palletsprojects.com/)

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
Click the green Code button on this page, 
Download zip file, uncompress it. 
(or run `git clone` if you have `git` installed on your computer.)\
After that,\
Run `flask_app.py` and open the link in the browser ( such as 
`http://127.0.0.1:5000` ) and enjoy!

## Screenshots
![image](https://github.com/user-attachments/assets/50cdd28a-b9bf-4e51-93c4-4b235f389510)
After Installation, it will work like this.

## References
The author's paper is available on [THIS](https://pubs.acs.org/doi/10.1021/acs.jchemed.9b00502)
site.\
DOI link: [https://doi.org/10.1021/acs.jchemed.9b00502](https://doi.org/10.1021/acs.jchemed.9b00502)\
Cite this: J. Chem. Educ. 2020, 97, 1, 263–264
