hadoop-yarn-unreg-nodes
=============================

Package Documentation
---------------------

This package gets a list of hadoop slave nodes using YARN API and compares it to autoscaled group
nodes to identify instances that failed to register with YARN master.


Installation
------------
```
pip install yarn-unreg-nodes
```
From source code

```
git clone  https://github.com/seeker815/hadoop-yarn-unreg-nodes.git
pushd hadoop-yarn-unreg-nodes
python setup.py install
popd
```

Usage
-----

### CLI interface

    bin/yarn_unreg_nodes --help

alternative

    python -m yarn_unreg_nodes --help

