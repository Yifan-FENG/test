# Instructions for setting up Jupyter notebooks 

For the programming part of this course we will be using Python. Python is an object oriented programming language that is by far the most commonly used in Data Science. It is designed to be easy to learn for beginners and readable.

Python is regularly updated (currently on version 3.9) but adoption of different versions is widespread. This means libraries or example code you find may not work with different versions of Python. The biggest difference is between Python 2 and 3 (there are actual syntactical differences), although most things we will want to use Python for now will be Python 3. 

It is possible to have multiple versions of Python installed on your computer at once. At any one time, your computer will be pointed towards one as default. 

You can find this out by typing `which python` on unix systems and ```where python``` on windows

Into the terminal. This will return a path to the current python executable. 

`python --version`

Will show which version of Python this is. 

I will assume that you only have the Python that your laptops are installed with to begin with (this will be 2.7 for OSX, none for windows). 

### Installing Anaconda

We will be installing Python using a package called Anaconda. This will give you Python, as well as some useful packages that you’ll need, as well as a way for you to manage and switch between different python environments (more on that later), and install new packages and libraries. 

1. Go to https://www.anaconda.com/products/individual
2. Download the Graphical Installer for your specific operating system, as of 13th October 2020, this will be Python 3.8) 
3. Run the installer you download, choosing the default locations

Check that you are using the anaconda version of Python by typing the following command into the terminal

`which python`

Now we are going to run a Jupyter notebook. This where we will run most of our Python scripts. 

There are two ways of doing this 

#### Anaconda Navigator 
1. You will have gotten a piece of software called Anaconda Navigator when you installed Anaconda. Open this.
2. Select Jupyter notebooks from the menu. This will open a terminal window and a browser window. 
3. In the browser window, navigate to the folder where you have downloaded the tutorial notebooks.

#### From Terminal/Console 
1. Navigate (using cd) to where the downloaded notebooks are
2. Type `jupyter notebook`

What has happened here is we have launched the notebook program from the terminal, and we have then opened a web browser and navigated to localhost:8888.  

It's important to understand this split, the program is running in the terminal, and we have a view on it through the browser. This client – server set up means that if we close the browser, the notebook doesn’t close. It also means we can run notebooks on servers in the cloud, and then interact with them through the browsers on our local machines.  

### Troubleshooting Python 

- Which install of Python are you using? `which python` (unix) `where python` (windows)
- Which version of Python are you using? `python —-version`
- Which install of pip are you using? `which pip` (unix) `where pip` (windows)
- Which version of package is installed using pip? `pip show [package name]`
- Which install of Anaconda are you using? `which conda` (unix) `where conda` (windows)
- Which version of package is installed using Anaconda? `conda list [package name]`

