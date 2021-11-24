# PyCharm Jupter Install Guide
Installation guide to run jupyter notebooks on PyCharm <br>
this guide works on Windows, the descriptions for Linux should work, but without guarantee
## Ananconda
### install Anaconda
- go to https://docs.anaconda.com/anaconda/install/
- follow the install guide for your system
- verify your install like this <br> https://docs.anaconda.com/anaconda/install/verify-install/

### add jupyter
- open anaconda navigator

- open the Environments tab

- if is none environmental variable given, create one and name it you like (e.g. "base")

- open a terminal with this environmental variable
    - Windows 10 open CMD.exe Promt in Anaconda Navigator
    - Linux should use ```$ conda activate ./<name_of_env>```

- in the terminal
    - ```$ conda install jupyter```
    - ```$ conda install pytorch torchvision -c pytorch```
    - ```$ conda update conda```

## PyCharm
install PyCharm with Anaconda Navigator or from here:<br> https://www.jetbrains.com/de-de/pycharm/<br>

and open it

- Click on File->New Project
- create a Pure Python Project at a Location you like
- set the Base interpreter to the Anacondo path
    - Windows: ```C:\ProgramData\Anaconda3\python.exe``` should be the standard path
    - Linux: the path where you installed Anaconda

after successfull indexing you can use the QuickFix on top of the Editor in PyCharm with the pale yellow background<br>
Jupyter is not installed &nbsp; Install Jupyter

After these steps you should able to work on Jupyter Notebooks in PyCharm




