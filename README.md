# SQream DB and H2O demo

This repo contains a notebook that shows how to interact with H2O.ai using SQream DB's pysqream connector.

## Prerequisites

### Install Conda and Python
* Windows: https://docs.anaconda.com/anaconda/install/windows/
* Linux: https://docs.anaconda.com/anaconda/install/linux/

### Activate Conda
* From the Windows command prompt: `conda activate`
* From the Linux shell: `$ eval "$(~/anaconda/bin/conda shell.bash hook)"`

### Install H2O from Conda

```
 $ conda install -c h2oai h2o
 $ pip install http://h2o-release.s3.amazonaws.com/h2o/rel-zahradnik/1/Python/h2o-3.30.0.1-py2.py3-none-any.whl
``` 

### Install pysqream

```
$ pip install pysqream
```

### (Optional) Define the credentials for your SQream DB cluster

On Linux:

```
$ export SQREAM_USERNAME="rhendricks"
$ export SQREAM_PASSWORD="Tr0ub4dor&3"
```

### Run a Jupyter Notebook server
```
$ jupyter notebook
```

## Running the notebook

[Download the notebook](https://github.com/SQream/sqream-db-h2o/blob/master/SQream%20DB%20and%20H2o.ai%20demo.ipynb) to a directory accessible by your Jupyter Notebook server.

* Remember to modify the login credentials to your SQream DB cluster.

* Remember to load the demo database to your SQream DB installation.
