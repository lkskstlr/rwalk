# RWALK
A simple random walk Python package implemented in C and parallelized in OpenMP. This repository is supplemented by a blog-post at [lukaskoestler.com](https://lukaskoestler.com/blog/random_walk.html). The post should also be considered the primary documentation for this repository.

## Installing
This package works only on -nix operating systems and is only tested on Ubuntu 18.04. First build the rwalk C library like
```shell-session
(cd rwalk; make clean; make all;)
```
and then install the requirements like
```
pip install -r requirements.txt
```
If you want to run the `post.ipynb` notebook that goes with the blog-post you have to run
```
pip install -r requirements_jupyter.txt
```
The two `requirements.txt` files do not give particular versions of the libraries to not overwrite them in your environment. The used features are very basic and should be available in future and past versions of the libraries.