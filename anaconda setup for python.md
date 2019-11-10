# Anaconda setup
## List of steps needed to install Anaconda / Python / Jupyter Notebook before LabMasters training
* Download Anaconda from official site https://www.anaconda.com/distribution/
* Start Anaconda installation
    - tick *Add Anaconda to my PATH environment variable* in Adanced Options (although not recommended in installation description)
    - don't install now Visual Studio Code or R Studio from Anaconda (my suggestion)
* Start Python installation
    - Run Anaconda Prompt terminal and enter
> ``` 
> conda update conda
> conda create --name myPython
> activate myPython
> conda install pandas numpy jupyter cython bottleneck numexpr openpyxl lxml xlrd xlwt pytables nose
> ```
> > Confirm Python installation version in terminal
> ```
> conda --version
> python --version
> ```
* Run Jupyter Notebook
    - Open Anaconda Navigator and click *Launch* within Jupyter Notebook section.
## Helpfull links
* https://github.com/macwilam/KursPython
* https://www.datacamp.com/community/tutorials/installing-anaconda-windows