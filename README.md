# Renewable-Energy-Project
Multiple Linear Regression study using US and global renewable energy datasets.  

## Project Journal Instructions
### Setup
1. Install [Anacandoa](https://docs.anaconda.com/anaconda/install/windows/) and run the following in Anaconda Prompt (this may take a while):
  ```
  conda install -c conda-forge jupyter
  pip install jupyter
  jupyter kernelspec --version # Should return a version number if installed correctly
  ```
3. Install [R](https://www.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/) and run the following (in either):
  ```
  install.packages('IRkernel')
  IRkernel::installspec(user = FALSE)  # Registers the kernel in Jupyter
  ```
4. Install [Python](https://www.python.org/downloads/)
5. Install [VSCode](https://code.visualstudio.com/download) (if not installed already) and the following extensions:
   * R
   * R Debugger
   * Jupyter
   * Python
7. Set up Jupyter is VSCode:
   1. In VSCode, open the Command Palette (Ctrl+Shift+P on Windows/Linux, Cmd+Shift+P on macOS).
   2. Type and select "Python: Select Interpreter" and choose the Python environment that has Jupyter installed (it’s likely shown as a Python version)
9. To run R code, you likely need to change the kernel (if the code cells say ‘Python’):
    1. In the top right corner click the ‘Python 3.X.X” button
    2. In the popup Command Palette, select ‘Select Another Kernel’
    3. Select ‘Jupyter Kernel’
    4. Select ‘R’ (if this doesn’t pop up, you may need to rerun the commands in Step 2 and/or close and reopen VSCode)
