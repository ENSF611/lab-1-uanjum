# ml-lab-1: Practice github classroom

1. Clone this repository to your local computer.
2. Open Jupyter notebook `ml-lab-1.ipynb`
3. Change author name to your name. 
4. Save. git add and commit change.
5. Copy the code below and run in a code cell in Jupyter notebook.
6. Save. git add and commit change.
7. Run the second cell to display all conda environments. 
8. Save. git add and commit change.
9. git push changes to github.


```Python
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

For Uzair Anjum, the package versions are:
```
Python version: 3.10.7 (v3.10.7:6cc6b13308, Sep  5 2022, 14:02:52) [Clang 13.0.0 (clang-1300.0.29.30)]
pandas version: 1.5.0
matplotlib version: 3.6.0
NumPy version: 1.23.3
SciPy version: 1.9.1
IPython version: 8.5.0
scikit-learn version: 1.1.2
yellowbrick version: 1.5
```

For me, the list of conda environments include:
```
# conda environments:
#
base                  *  /Users/MB/opt/miniconda3
ensf611-ml               /Users/MB/opt/miniconda3/envs/ensf611-ml
```
Note the `*` indicating that `ensf-ml` is the currently active environment