# Exploratory Data Analysis of Molecular Network and Polypharmacy data

#### [Project website](http://snap.stanford.edu/decagon)

## Overview

This folder contains code necessary to run the Exploratory Data Analysis needed for Decagon Algorithm. Decagon is a method for learning node embeddings in multimodal graphs, and is especially useful for link prediction in highly multi-relational settings. See 
the [paper](https://doi.org/10.1093/bioinformatics/bty294) from the author  [Marinka Zitnik](http://stanford.edu/~marinka) (marinka@cs.stanford.edu) for details on the algorithm.

### Running the code
Clone this https://github.com/calltovijay/decagon git repo.
The full polypharmacy dataset (described in the paper) is available on the 
[project website](http://snap.stanford.edu/decagon). To run the code on the full dataset first download all data files
from the [project website](http://snap.stanford.edu/decagon) and untar the same under the <project dir>/polypharmacy folder. The polypharmacy folder will look like below.
<checked out dir>/polypharmacy
	bio-decagon-combo.csv
	bio-decagon-effectcategories.csv
	bio-decagon-mono.csv
	bio-decagon-ppi.csv
	bio-decagon-targets-all.csv
	bio-decagon-targets.csv
	Exploratory Analysis.ipynb
	README.md
	utility.py
Now, we all set to run the Exploratory Analysis.ipynb python notebook and study the Molecular Network and Polypharmacy data.

## Requirements
Exploratory Data Analysis is done with Python 3.x. Please follow the instructions given in the Exploratory Analysis.ipynb notebook and use the Google CoLab as the permutation testing function might take nearly 2 to 3 hrs. 
