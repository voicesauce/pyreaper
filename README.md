# pyreaper for OpenSauce

This is a fork of the Python package
[pyreaper](https://github.com/r9y9/pyreaper) by Ryuichi Yamamoto.

pyreaper itself is a Python wrapper for the [REAPER (Robust Epoch And Pitch EstimatoR)](https://github.com/google/REAPER>) project from Google.

The purpose of this project is to have an easy-to-install Python package, so
that [OpenSauce](https://github.com/voicesauce/opensauce-python) can easily
call Google's REAPER code to estimate F0.  We forked pyreaper and REAPER,
because we needed to make a few minor modifications for OpenSauce.

## Installation

Before installing, first make sure you have the Python packages `numpy` and
`cython` installed. For example, you can install these packages via the
command:

```bash
pip install numpy cython
```

Then run:

```bash
pip install git+https://github.com/voicesauce/pyreaper
```

or insteading of using pip, do:

```bash
git clone https://github.com/voicesauce/pyreaper
cd pyreaper
git submodule update --init --recursive
python setup.py develop # OR python setup.py install
```

This should resolve the package dependencies and install pyreaper property.

## Other documentation

See documentation for Google's [REAPER](https://github.com/google/REAPER>)
project and Ryuichi Yamamoto's [pyreaper](https://github.com/r9y9/pyreaper).
