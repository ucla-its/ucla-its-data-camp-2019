# Software Setup
### Installing Python
In this course, we are going to be performing all of our analyses in [Python programming language](https://www.python.org/). The first step, therefore, is to make sure Python is installed and configured properly on your machine. There are currently two major Python versions: Python 2 and Python 3. For this class, we will be using Python 3. Although in most cases your code will work for both versions, there will occassionally be differences that catch you by surprise, so it is good to be aware of which version you are installing.
##### Installing the Anaconda Distribution of Python
Anaconda is a free distribution of Python that includes some additional software and commonly used packages for scientific computing and data science. Follow the steps [here](https://www.anaconda.com/distribution/) to install the Anaconda's Python 3.7 distribution for your operating system.

When you install Python via Anaconda, the location of your Python installation will very likely be different than if you installed Python via www.python.org, and you will end up with multiple installations of Python. For example, I have Python installed at:
  
"C:\Users\Tim Black\Anaconda3\python.exe" (Anaconda)  
"C:\Users\Tim Black\AppData\Local\Programs\Python\Python37-32\python.exe" (Standard Install)   
  
Having multiple installations is completely fine as long as you **remain aware of which version you are working in, especially for the installation of packages.** For the rest of this course, we will be working with the Anaconda installation of Python, which is why you should get familiar working within the Anaconda Command Prompt.
##### Using the Anaconda Command Prompt
Once you have installed Python via Anaconda, we will use the specialized Anaconda command prompt to access our installation of Python as well as any of the included software. Let's access the Anaconda Command Prompt and confirm that we have installed Python successfully.

Find our location of Python
1. Open the Anaconda Command Prompt.
2. Type `where python`. You should see at least one filepath to your Python installation(s).

Access the Python Interpreter
1. Make sure the Anaconda Command Prompt is running.
2. Type `python`. You've now opened your installation of python. You should see the version of Python printed, as well as the Python interpreter open.
3. Type `print("Hello World")`
4. Type `quit()`. You have now exited the Python interpreter and are back to the Anaconda Command Prompt.

Open the Jupyter Notebook Application
1. Make sure the Anaconda Command Prompt is running.
2. Type `jupyter notebook`. After seeing some notes appear in the command prompt, your default browser should open up with the Jupyter notebook
3. Great! You've now verified that you have the Jupyter notebook installed.  

### Installing Python Packages
Now that Python is installed, you should get familiar with installing python _**packages**_. Python packages are pre-built pieces of code that you can leverage to make your work easier. Python itself comes pre-loaded with a set of core packages called the [Python Standard Library](https://docs.python.org/3/library/). However, having all possible Python packages included in the standard Python install would make the distribution heavy and unwieldy, which is why the Python Standard Library is limited to core packages that are used on many different kinds of projects.

The Anaconda distribution (which we just installed) goes beyond the Standard Library and comes pre-loaded with additional packages that are commonly used for scientific computing and data science; you can see a full list of the packages (depending on your OS and Python version) [here](https://docs.anaconda.com/anaconda/packages/pkg-docs/).

- mention pandas here

Although you will have access to hundreds of libraries immediately after installing Python, you will likely reach a point where you need to install additional packages to perform specialized tasks for you. When you want to install additional packages that are not part of either the Python Standard Library or part of the Anaconda distribution, you can do so in two different ways. 

##### Method 1: Via Anaconda
Anaconda maintains it's own package repository called [Conda](https://anaconda.org/anaconda/conda). You can install packages from the repository using the following syntax:

`>conda install -c conda-forge [package name]`  
  
What is going on here?
- `conda` indicates we will be using the Conda program
- `install` is the command for installing new packages
- `-c conda-forge` indicates that we want to install from the `conda-forge` channel
- `[package name]` is the name of the package you want to install

Let's install two packages that we will be using later in the course, `geopandas` (for spatial data analysis) and `folium` (for creating leaflet maps). Make sure you have the Anaconda Command Prompt open, then type the following commands:

`>conda install -c conda-forge geopandas`  
`>conda install -c conda-forge folium`

##### Method 2: Via Pip
You occassionally will find that a package is not available through Conda, or you may be working on a Python project that doesn't require Anaconda. In this case, you will use [Pip](https://pip.pypa.io/en/stable/), the recommended tool for installing packages from the Python Package Index (PyPI). Pip is automatically installed with Python, and you use it to install packages through the command line prompt. The command is not too different from Conda:

`>python -m pip install [package name]`

See [here](https://www.anaconda.com/understanding-conda-and-pip/) for more information about the difference between Anaconda's Conda package manager and Pip.
### Installing a Text Editor (optional)
For this course, all of our work will be done within Jupyter Notebooks. However, it is helpful to also have a good text editor for any projects that are not strictly data science. A Text editor is far simpler than a Jupyter notebook, yet it is extremely versatile and is the primary tool of any programmer. In fact, you already have one installed on your machine (Notepad, Wordpad, etc). 

Beloved text editors will provide language-specific color highlighting, among other features. I prefer to use [Sublime Text](https://www.sublimetext.com/), but there are plenty of other good (free) options out there, such as [Visual Studio Code](https://code.visualstudio.com/) or [Atom](https://atom.io/). It doesn't really matter which one you use - it just comes down to personal preference.
### Installing git & GitHub (optional)
[GitHub](www.github.com) is the most popular platform for sharing code online. I recommend you sign up for an account, which you can use to read other people's code and share your work with others (you will be able to access the work for this couse without setting up an account).  

If you want to practice uploading your work to GitHub, you will want to install git, the most commonly used version control system used by programmers. There are a couple different ways to install git


1. Installing the GitHub desktop application, which comes pre-packaged with git. 
2. Installing git and using commands to push to GitHub.