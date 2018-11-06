# Programming for Data Analysis Assignment 2018 - Explain numpy.random package

## Requirments of the assignment

1. Explain the overall purpose of the package 
2. Explain the use of teh "Simple random data" and "permutations" functions. 
3. Explain the use and purpose of at least five "Distributions" functions. 
4. Explain the use of seeds in generating pseudorandom numbers

### other requirments 
1. use github version control
2. upload repo url to the assignment section on student page. 
3. commit history of at least 10
4. meaningful commit messages
5. assignment deadline 11/11/2018 at midnight
6. README file containgin an explanation of whats in the repository and how to run jupyter notebook. 
7. jupyter notebook with the report on numpy.random
    a. explain the dataset? 
    b. well conceived, interesting and well researched project
    c. assignment covers jupyter notebook so include fancy stuff like images, links, code and plots
    d. any python package that you fancy. 
8. gitignore file



## Getting Started
First get the required software
As I have windows 10 on my pc I'm only adding links to this version of various software. 

### Prerequisites
This project requires jupyter notebook, python, and for convience cmder. It also requires a github account. 
Anaconda has python, ipython, jupyter notebook and a large number of common python packages required in Data Analysis. 
1. Get anaconda 3.7 version for windows [conda](https://www.anaconda.com/download/)
2. get git 2.19.1 [git](https://git-scm.com/download/win)
3. optional get cmder 1.3.6[cmder](https://github.com/cmderdev/cmder/releases/download/v1.3.6/cmder.zip) (this comes with git so you can drop option 2 above if you go with option 3.  
4. set up github account and create a repo [github](https://github.com/)


### Installing

Install the above packages. Any problems google it. update any packages; from cmder 
```
conda update –all 
git - version
```

## Repository structure

The gitignore file ignores the .git and .ipynb_checkpoints in the local folder. Python files are also ignored. A standard gitignore file was used. It can be found here [gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore) 

* data 
    * ANSURD2Distribution.zip which can be downloaded  at this link [Ansurd2](http://mreed.umtri.umich.edu/mreed/downloads.html)contaning public data on us military personale heights from 2012 - used to illustrate normal distribution. 
    One file is unzipped and the spaces in the name removed ANSURIIMALEPublic.csv
* img - various images used within the report; this may change so I'll not list them out. some i made up some were taken from the internet, some have acknowledgements added in the jupyter notebook.
* .gitignore - gitignore file taken from [gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore)
* License - GNU GENERAL PUBLIC LICENSE Version 3
* README.md - this readme
* numpy-random.ipynb - The main body of the assignment
* numpy-ref-1.15.1.pdf - taken from [numpybook](https://docs.scipy.org/doc/_static/numpybook.pdf)
* numpybook.pdf - taken from [numpy reference](https://docs.scipy.org/doc/numpy/numpy-ref-1.15.1.pdf)


I may or may not remove the book links by the time the assignment is due; same with some of the photos. 

## Jupyter 

The main body of work is in the jupyter notebook numpy-random.ipynb. 

### Running a Jupyter notebook

#### Start jupyter notebook
2 way's via the anaconda app or via the command line on cmder. I will describe the cmder approach.
open cmder in home directory or from a folder within the home directory
```
C:\Users\Helen\Desktop\GMIT\github\
```
Create a repo on github [repo](https://github.com/Osheah/p4da-numpy-random)
clone the repo on github by clicking the green clone or download link
in cmder
```
git clone https://github.com/Osheah/p4da-numpy-random.git
git init
```
open jupyter using the command
```
jupyter notebook
```
A browser should open linking the current directory in cmder to an jupyter version of windows explorer its  home page.

http://localhost:8888/tree

### create a jupyter notebook
navigate to your cloned folder from within the jupyter explorer. On the right theres a button 'new' click this and select python 3. A new jupyter notebook will open with the default title untitled. click on the name 'untitled' and rename it numpy-random.ipynb. Details on how to create cells in jupyter notebook can be found here [jupyter notebook](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#basic-workflow). Save any work (although it is usually saved automatically). 

### ending a jupyter notebook session
Save your unsaved jupyter notebooks. Close jupyter in your browser. Go to cmder and enter **control + c**. This shuts the ipython kernal that jupyter uses. upload your notebook to github via the commands below; make sure that you are in the directory that git is initialised in e.g. C:\Users\Helen\Desktop\GMIT\github\p4da-numpy-random\
```
git status
git add .
git commit -m "add a relivent commit message"
git push
```
### opening a jupyter notebook

jupyter notebooks have the extension ipynb. When you find a notebook that you want to look at or edit, dont click on it; instead right click and save it to your local pc. Then open jupyter notebook via the cmder command and navigate to the notebook. NB; before opening the notebook make sure the notebook is saved in a sub directory of the cmder path. jupyter notebooks cannot access any files that are not within the path when the kernal is called. 


## Authors

* **Helen O'Shea** - *helen.oshe@gmail.com* - [Osheah](https://github.com/Osheah/)

See also the list of [contributors](https://github.com/Osheah/p4da-numpy-random/graphs/contributors) who participated in this project. Its just me at the mo.

## License

This project is licensed under the  GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to all the good folk at wikipedia and stackoverflow
* Thanks to my husband for taking the kids away for the weekend. 
