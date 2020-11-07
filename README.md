https://mybinder.org/v2/gh/HepaxCodex/JupyterEnv/master?urlpath=git-pull?repo=https://github.com/HepaxCodex/Jupyter

# JupyterEnv

This will hold the Jupyter Environment necessary for MyBinder to quickly build and load a suitable docker image.

This repo will then point to HepaxCodex/Jupyter which will contain the notebooks of interest.

This approach should significantly improve the speed of launching MyBinder by avoiding a rebuild on every repo commit.

https://discourse.jupyter.org/t/tip-speed-up-binder-launches-by-pulling-github-content-in-a-binder-link-with-nbgitpuller/922
