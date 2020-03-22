![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
# biopython-coronavirus

A tutorial [jupyter](https://jupyter.org/) notebook illustrating how to use [biopython](https://github.com/biopython/biopython) to identity and perform some basic characterization of a coronavirus genome sequence.

## Viewing the notebook

Simply open the notebook link:
https://github.com/chris-rands/biopython-coronavirus/blob/master/biopython-coronavirus-notebook.ipynb

Alternatively view the notebook by pasting the address into [nbviewer](https://nbviewer.jupyter.org/).

## Running the notebook via Google collab

TO DO

## Installing the notebook locally

First clone this repository:
```
git clone https://github.com/chris-rands/biopython-coronavirus
```

Requires Python (version 3.6 or higher) with the `jupyter` and `biopython` modules. One of two options is recommended:

1) Installation via pip

```
pip3 install jupyter biopython
```

For installation without root access add the `--user` flag.

2) Installation via conda
  
```
conda env create -f biopython-coronavirus-environment.yml
conda activate biopython-coronavirus
```

## Running the notebook locally

Open the notebook as follows:
```
jupyter-notebook biopython-coronavirus-notebook.ipynb
```

## Related Biopython resources

- [Official tutorial documentation](http://biopython.org/DIST/docs/tutorial/Tutorial.html)
- [Peter's workshop](https://github.com/peterjc/biopython_workshop)
- [Notebook tutorials](https://github.com/tiagoantao/biopython-notebook)
