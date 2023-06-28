---
subtitle: Docs
permalink: /docs/getting_started/installation
menubar: docs_navigation
---

# Installation
DynaBench requires

    numpy>=1.23.5
    py-pde>=0.27.1
    torch>=2.0.1

## Install using pip
DynaBench is available on pypi, so you can install it by running

    pip install dynabench

We recommend to use a [virtual environment](https://docs.python.org/3/tutorial/venv.html) for this.

## Install using conda
Currently DynaBench is not available via conda.

## Install from source
If you want to get the latest version of DynaBench, or if you want to help develop the framework, you should install from source.

    git clone https://github.com/badulion/dynabench
    cd dynabench
    # create and activate a virtual environment
    python -m pip install -r requirements.txt
    # install pytorch version for your system (see below)
    python -m pip install .