# Exploratory Data Analysis of Molecular Network and Polypharmacy data

#### [Project website](http://snap.stanford.edu/decagon)

## Overview

This folder contains code necessary to run the Exploratory Data Analysis needed for Decagon Algorithm. Decagon is a method for learning node embeddings in multimodal graphs, and is especially useful for link prediction in highly multi-relational settings. See 
the [paper](https://doi.org/10.1093/bioinformatics/bty294) from the author  [Marinka Zitnik](http://stanford.edu/~marinka) (marinka@cs.stanford.edu) for details on the algorithm.

### Running the code
Clone this https://github.com/calltovijay/decagon git repo.

The full polypharmacy dataset (described in the paper) is available on the 
[project website](http://snap.stanford.edu/decagon). To run the code on the full dataset first download all data files
from the [project website](http://snap.stanford.edu/decagon) and untar the same under the project **checked out dir**/polypharmacy folder. The folder structure will look like below.
	
**checked out dir**/polypharmacy<br>
<pre>
	bio-decagon-combo.csv<br>
	bio-decagon-effectcategories.csv<br>
	bio-decagon-mono.csv<br>
	bio-decagon-ppi.csv<br>
	bio-decagon-targets-all.csv<br>
	bio-decagon-targets.csv<br>
	Exploratory Analysis.ipynb<br>
	README.md<br>
	utility.py
</pre>	
Now, we all set to run the Exploratory Analysis.ipynb python notebook and study the Molecular Network and Polypharmacy data.

## Requirements
Exploratory Data Analysis is done with Python 3.x. Please follow the instructions given in the Exploratory Analysis.ipynb notebook and use the Google CoLab as the permutation testing function might take nearly 2 to 3 hrs. 
