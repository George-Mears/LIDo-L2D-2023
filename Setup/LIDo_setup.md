# LIDo Computer Setup 2023
- - - -



## Summary 
- - - -

For people that found last weeks intro to L2D confussing (I know I did), here is some help to get computers setup properly. This should provide everyone with the tools to follow along with the workshops.

***NOTE***: these instructions are only relevant for people who recieved a Macbook Pro from LIDo, which use the Apple M2 processor (check *about this Mac* to find processor). For windows and older macOS systems follow relevant instuctions.

If you need any help with the setup or understanding any of the following please get in touch. We are all in this together! 

Also, if you have experience with Python and programming, makes yourselves known to the group and we can help people with less/no experience (maybe form a leadership group?) I know there are a few fellow bioinformaticians and computer wizards in the group.

## Getting setup - things to download

- - - -

This is a summary of the basic software required to complete the L2D course so far. I would download these in the following order:

<li><a href="#anaconda">1. Anaconda</a> (required)</li>
    <li><a href="#vscode">2. VScode</a> (recommended)</li>
    <li><a href="#github-desktop">3. GitHub Desktop</a> (recommended)</li>
    <li><a href="#jupiter-notebook">4. Jupiter notebook</a> (required)</li>
    <li><a href="#bonus-more-experienced-users">Bonus </a> (experienced users)</li>

## Anaconda


What is conda?

* Conda is an open-source package and environment management system that runs on Windows, macOS, and Linux. Conda quickly installs, runs, and updates packages and their dependencies. It also easily creates, saves, loads, and switches between environments on your local computer. It was created for Python programs, but it can package and distribute software for any language.

What are conda environents?

* A Conda environment is a directory that contains a specific collection of Conda packages that you have installed. 
  
  *e.g. you are doing an analysis and the software you are using is quite sensative (meaning it doesnt get along with other packages or softwaere), therfore requires its own environemt with only the required dependancies for that partical software.*

What is Anaconda desktop (for people new to Anaconda and environments)?

* The desktop application lets you easily manage integrated applications, packages, and environments without using the command line.

* Its a nice way to visualise and manage what is going on under the hood with the different conda environments

**To download anaconda:**

1. Go to: https://www.anaconda.com/download

2. Click download for Mac (M1/M2)

3. Follow installation steps

4. to check correct istallation - open terminal and `(base)` should show up

    * e.g. `(base) macbooks-MacBook-Pro:~ macbook$`
  
5. This is your base conda environment - you can activate it and deactivate it by the following:
   
   * `conda activate` - to activate base environment
   * `conda deactivate` - to deactivate base environment

## VScode

- - - -

Why VScode?


* This is my personal preference [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment#:~:text=Article%20Talk,automation%20tools%2C%20and%20a%20debugger.)

* Free and built on open source. 
* Integrated Git (can interact with GitHub directly), debugging and extensions. 
* Can use interactive Python notebooks (.ipynb) for L2D classes.

**To download VScode:**

1. Go to: https://code.visualstudio.com/download#

2. For MacOS with [M2](https://en.wikipedia.org/wiki/Apple_M2) arm-based system (this should be all people with a new Mac from LIDo) - Click big Mac button (or Apple silicon .zip file)

3. Follow installation steps

### Github Desktop

- - - -

Why GitHub Desktop?

* this will help with changing and uploading L2D assignments

* Focus on what matters instead of fighting with Git. Whether you're new to Git or a seasoned user, GitHub Desktop simplifies your development workflow.

* For those not familiar with GitHub terminology, here are the basic commands used when uploading or retriving something from Github. (GitHub desktop makes this process really easy and user friendly!! This can also be done directly in VScode as well!)
  * Push
  * Commit
  * Pull
  * Clone

**To download GitHub Desktop:**

1. Go to: https://desktop.github.com/

2. Click download for MacOS
  
3. Move GitHub desktop from downloads folder to applications folder
  
4. Follow installation steps

5. Sign into GitHub.com

6. If everything ran smoothly you should have a GitHub folder in your Documents folder on your laptop

## Jupiter Notebook

The IPython Notebook is now known as the Jupyter Notebook. It is an interactive computational environment, in which you can combine code execution, rich text, mathematics, plots and rich media. For more details on the Jupyter Notebook, please see the Jupyter website.

File extension `.ipynb`

1. So once VScode is open, create a new file with the file extension `.ipynb` and save it. 

2. This will trigger a warning to install things required for a jupiter notebook.

3. Install ipykernal for pythoon3 and certain pip packages

4. Type `print("Hello world)"` in one of the coding (python) cells and run the cell (clck play button or shift + enter)


## Bonus (more experienced users)

I would consider using the following: 

* Miniconda (a free minimal installer for conda) - this is to be downloaded instead of Anaconda, and only a commandline tool (alternatively use the anaconda commandline tool)
  
* mamba (rapid installation of conda packages!) - a reimplementation of the conda package manager in C++. Parallel downloading of repository data and package files using multi-threading

**To download Miniconda:**

Go to: https://docs.conda.io/projects/miniconda/en/latest/

**To install the mamba package:**

Go to: https://anaconda.org/conda-forge/mamba


* Next time you wish to install a conda package run `mamba install` instead of `conda install`

* e.g. `mamba install my_package`

* then watch the magic unfold!


