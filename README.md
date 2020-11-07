[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HepaxCodex/JupyterEnv/main?urlpath=git-pull?repo=https://github.com/HepaxCodex/Jupyter)

# JupyterEnv

This will hold the Jupyter Environment necessary for MyBinder to quickly build and load a suitable docker image.
This repo will then point to HepaxCodex/Jupyter which will contain the notebooks of interest.

This approach should significantly improve the speed of launching MyBinder by avoiding a rebuild on every repo commit.
https://discourse.jupyter.org/t/tip-speed-up-binder-launches-by-pulling-github-content-in-a-binder-link-with-nbgitpuller/922


# Configuration

* environment.yml
This is a list of anaconda items to install into the conda environment
After installing, they may need enabled ? or Build? into jupyter postbuild?

* postBuild
These are commands for fire up jupyter Lab with the appropriate extensions