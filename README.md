# BHF_Python_workshop

Code and data for the BHF workshop.

The goals of this short course on Python is to give a basic introduction. By the end of this workshop you should:
- Program using Python Integrated Development Environments (IDEs) and gain familiarity with Ipython Notebooks
- Manipulate simple variable types, operators and conditions
- Write loops and functions
- Gain familiarity with data science libraries: Numpy, Pandas and MatplotLib

The exercises for this workshop are organized into Jupyter Notebooks which is a way of serving executable Python code on a web page. A local Jupyter server can be run by installing it with Anaconda (or Miniconda), or through the internet using Google's Colaboratory service. 

Slides can also be viewed online at https://nbviewer.jupyter.org/github/estherpuyol/BHF_Python_workshop

## Getting Started With Colaboratory
In this workshop, we will be using Google Colaboratory to run our notebooks, but if you want you can run all the notebooks.

To get going with Colab:

1.   Go to https://colab.research.google.com (be sure to be logged into your Google account beforehand)
2.   Click on the Github tab and enter https://github.com/estherpuyol/BHF_Python_workshop/ into the search box
3. A number of notebooks should appear, double click the one to load.
4. You can start using the notebooks by clicking on the run icons to the left of each cell or press ctrl+Enter. (You will get popups about the notebook not being authored by Google and other things, just click Yes to these)

## Installing Python Locally
If you want to run locally, you need to install Python 3.7, Numpy, Jupyter, and Matplotlib. These can be installed separately through the standard distributions from the sites for each package, or using a managed package system like Anaconda/Miniconda.

The fastest way is with Miniconda:

1. Go to https://docs.conda.io/en/latest/miniconda.html and download the Python 3.7 64bit installer for your OS.
2. Install Miniconda, checking the box to set the PATH variable
3. In the Start Menu, go to "Anaconda3" -> "Anaconda Prompt"
4. Type `conda install jupyter matplotlib` to install the components needed.
5. To start Jupyter, from this console type jupyter notebook

The complete but slow way is with Anaconda.

1. Go to https://www.anaconda.com/distribution and download the Python 3.7 graphical installer for your OS.
2. Install Anaconda, following instructions here: https://docs.anaconda.com/anaconda/install/
3. Start the Anaconda Navigator program
4. Navigate to "Environments" and click on "base (root)"
5. On the right side click "Update index..."
6. Once that completes set the drop-down menu to show all and type "Pandas" into the search box
7. Pandas 1.3.3 should show up, select it and install
8. Return to home and launch Jupyter Notebook. This should bring to your browser with the notebook server running. From here you can navigate to the workshop directory and start a notebook.

## Links

* Numpy manual: https://docs.scipy.org/doc/numpy/
* Matplotlib manual: https://matplotlib.org/3.1.0/users/index.html
* Python tutorial: https://www.python.org/about/gettingstarted
* Python tutorial: http://www.learnpython.org
