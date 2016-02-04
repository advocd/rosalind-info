# rosalind-info

## IPython for work with notebooks

### Setup
Install Anaconda - a python distribution over [url](https://www.continuum.io/downloads)

#### Install biopython package
the powerful package is a dependency in many examples. So if you want run the samples install this package

**via anaconda:**

  `conda install -c https://conda.anaconda.org/anaconda biopython`
  
#### IPyhton download as PDF (optional)
If the notebook should available as pdf download from the IPython webinterface following dependencies are needed:

**latex distribution**

for win [miktex-installer](http://miktex.org/download)

**pandoc**

you should use the [installer from the pandoc-site](http://pandoc.org/installing.html) for your operating system

### Start IPyhton webinterface (jupyter)
1. start the command line
2. change to the directory where the notebook is (or should be)
3. start the webinterface with the command:
    
    `ipython notebook`
