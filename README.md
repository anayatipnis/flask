# Flask Installation

# Using Conda
https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/
```
conda -V
conda update conda
conda search "^python$"
conda create -n learnpython python=3.6.1 anaconda
source activate learnpython
```

### Start server
Execute following command to start the server :
```
$ export FLASK_APP=server.py
$ python -m flask run
```
