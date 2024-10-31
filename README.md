# Renewable-Energy-Project
Multiple Linear Regression study using US and global renewable energy datasets.  

## Project Journal Instructions
### Setting Up R in VSCode
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
  
### Connecting to GitHub
1. Download [Git](https://git-scm.com/downloads) and run the .exe file
2. In VSCode, install the "GitHub Pull Requests" extension
3. In the project repository on GitHub (here!), click the green "Code" button and copy the URL.
4. Open a new terminal in VSCode by going to View > Terminal or pressing Ctrl + ` and run the following command:
   ```
   git clone <the link you copied>
   ```
5. Navigate to the cloned repository: ```cd repository-name```
6. Run the "Jupyter_Test.ipynb" notebook to confirm that everything works.
7. Copy the "Project_Journal.ipynb" file and rename the copied file to ProjectJournal_YourName.ipynb, replacing YourName with your actual name (this will be your personal project journal that you'll update as you work).
8. Commit and push your changes:
   1. Make sure to save the notebook (Ctrl + S) after making changes.
   2. Click on the Source Control icon in the Activity Bar (or press Ctrl + Shift + G).
   3. You will see your modified files. Hover over your file and click the + icon to stage it.
   4. In the message box at the top, enter a commit message (e.g., "Updated project journal") and click the checkmark icon to commit.
   5. Click the "..." menu in the Source Control view and select Push to push your changes to the remote repository.
9. Before making any new updates, ensure you have the latest version from the repository:
    ```
    git pull origin main
    ```
