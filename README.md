# ml-in-action (Machine Learning in Action)
A demo repository to implement different machine learning algorithms

# Getting started
```bash
# get the project dependencies
pip install -r requirements.txt

# open ipython notebook to access the entries
ipython notebook
```

# Entries
So far, all entries are done in SciKit Learn. Plan to do TensorFlow later.

## Poker hands

### Features
- Discover the hidden patterns under the rules
- Achieve the automatic rule generation
- avoid hand-coded heuristics

### Credits
1. [https://www.kaggle.com/c/poker-rule-induction](https://www.kaggle.com/c/poker-rule-induction)
2. [http://archive.ics.uci.edu/ml/datasets/Poker+Hand](http://archive.ics.uci.edu/ml/datasets/Poker+Hand)

# Installation Error
1. `no lapack/blas resources found` @ scipy
  - `sudo apt-get install libblas-dev liblapack-dev libatlas-base-dev gfortran`

2. `Not found: freetype, png` @ matplotlib
  - png: `sudo apt-get install libpng-dev`
  - freetype: [https://launchpad.net/ubuntu/+source/freetype](https://launchpad.net/ubuntu/+source/freetype)
  - still not found after install freetype: `sudo apt-get install pkg-config # probably pkg issue`

