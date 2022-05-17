# ENSF-611 Assignment -1

A practice assignment on GitHub Classroom

## What to do

1. Clone this repository to your local computer.
2. Open Jupyter notebook `ml-lab-1.ipynb`
3. Change author name to your name.
4. Save. git add and commit change.
5. Copy the code below and run in a code cell in Jupyter notebook.
6. Save. git add and commit change.
7. Run the second cell to display all conda environments.
8. Save. git add and commit change.
9. git push changes to github.

```python
import sys
print("Python version:", sys.version)

import pandas as pd
print("pandas version:", pd.__version__)

import matplotlib
print("matplotlib version:", matplotlib.__version__)

import numpy as np
print("NumPy version:", np.__version__)

import scipy as sp
print("SciPy version:", sp.__version__)

import IPython
print("IPython version:", IPython.__version__)

import sklearn
print("scikit-learn version:", sklearn.__version__)

import yellowbrick
print("yellowbrick version:", yellowbrick.__version__)
```

For me, the package versions are:

```
Python version: 3.8.5 (default, Sep  3 2020, 21:29:08) [MSC v.1916 64 bit (AMD64)]
pandas version: 1.1.3
matplotlib version: 3.3.2
NumPy version: 1.19.2
SciPy version: 1.5.2
IPython version: 7.19.0
scikit-learn version: 0.23.2
yellowbrick version: 1.3
```

For me, the list of conda environments include:

```
# conda environments:
#
base                     C:\Anaconda
ENSF-592                 C:\Anaconda\envs\ENSF-592
ENSF-611              *  C:\Anaconda\envs\ENSF-611
```

Note the `*` indicating that `ensf-ml` is the currently active environment
