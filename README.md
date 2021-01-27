

## CE9010: Introduction to Data Analysis <br> Semester 2 2020/21 <br> Xavier Bresson
   



<br>
<br>

## Local Python installation
<br>

Follow the following instructions to install Miniconda and create a Python environment for the course:

1. Download the Python 3.6 installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings. Note for Windows: If you don't know if your operating system is 32-bit or 64-bit, then open Settings-System-About-System type to find out your xx-bit system.
   * Windows: Double-click on the `Miniconda3-latest-Windows-x86_64.exe` file. 
   * macOS: Run `bash Miniconda3-latest-MacOSX-x86_64.sh` in your terminal.
   * Linux: Run `bash Miniconda3-latest-Linux-x86_64.sh` in your terminal.
1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Install git: `conda install git`.
1. Download the GitHub repository of the course: `git clone https://github.com/xbresson/CE9010_2021`.
1. Go to folder CE9010_2021 with `cd CE9010_2021`, and create a Python virtual environment with the packages required for the course: `conda env create -f environment.yml`. Note that the environment installation may take some time.  



   Notes: <br>
      The installed conda packages can be listed with `conda list`.<br>
      Some useful Conda commands are `pwd`, `cd`, `ls -al`, `rm -r -f folder/`<br>
      Add a python library to the Python environment: `conda install -n CE9010_2021 numpy` (for example)<br>
      Read [Conda command lines for packages and environments]<br>
      Read [managing Conda environments]

[managing Conda environments]: conda/conda_environments.pdf

[Conda command lines for packages and environments]: conda/conda_cheatsheet.pdf





<br> 
<br> 

## Running local Python notebooks 
<br>


1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Activate the environment. Type: `source activate CE9010_2021` or `conda activate CE9010_2021`.
1. Go to folder `CE9010_2021/` and start Jupyter with `jupyter notebook`. The command opens a new tab in your web browser.
1. Open, edit and run the notebook `tutorial01.ipynb` in your browser.



	Notes: <br> 
      Windows: Folder CE9010_2021 is located at `C:\Users\your_user_name\CE9010_2021`. MacOS, Linux: `/Users/your_user_name/CE9010_2021`.<br>
      List of [git commands]<br>






<br>
<br>

## Cloud Machine #1 : Google Colab
<br>

* Follow this Notebook installation :<br>
https://colab.research.google.com/github/xbresson/CE9010_2021/blob/master/colab/installation.ipynb

* Open your Google Drive :<br>
https://www.google.com/drive

* Open in Google Drive Folder 'CE9010_2021' and go to Folder 'CE9010_2021/tutorials/'<br>
Select the notebook 'file.ipynb' and open it with Google Colab using Control Click + Open With Colaboratory.<br>

   Notes: <br>
      Use Google Chrome Navigator.<br>
      The first time you open Colab, double-click on any 'file.ipynb'. Then select 'Connect more apps' and type Colab. 




<br>
<br>

## Cloud Machine #2 : Binder
<br>

&nbsp;&nbsp;&nbsp; Simply [click here].

[Click here]: https://mybinder.org/v2/gh/xbresson/CE9010_2021/main







[git commands]: git/git_commands.pdf
[git]: https://git-scm.com
[python]: https://www.python.org
[scipy]: https://www.scipy.org
[anaconda]: https://anaconda.org
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org


<br>
<br>
<br>
<br>
<br>
<br>



