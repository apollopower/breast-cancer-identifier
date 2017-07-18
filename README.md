# Breast Cancer Data Analysis with TensorFlow

This script utilized neural networks with [TensorFlow](https://www.tensorflow.org/) to analyze data from breast cancer scans and determine the
possible presence of breast cancer for new entries.

Data on breast cancer was pulled from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php)

## Getting Started

### Prerequisites

TensorFlow and this script runs on Python 3, and uses the SciPy pack for data manipulation.

If you don't have Python 3, [read this to get it installed](http://python-guide-pt-br.readthedocs.io/en/latest/starting/install3/osx/)

[You can get TensorFlow running on your machine here](https://www.tensorflow.org/install/)

To get SciPy working, you can have it installed on your command line:

```bash
pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose
```

### Running the Machine Learning Script

As a Python script, you may execute it on your command line (once inside the correct directory)
like so:

```bash
python nn_script.py
```

An Accuracy Score will be returned to represent the presence of breast cancer
on the tested data.
