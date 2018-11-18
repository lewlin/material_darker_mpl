# Matplotlib Material Darker Theme

Provides a `matplotlib` style file that fits nicely in JupyterLab if you are using the [material darker theme](https://github.com/oriolmirosa/jupyterlab_materialdarker).

## Install
1. Copy `material_darker.mplstyle` into `~/.matplotlib/stylelib/` (create folder if necessary).
2. Make sure that `~/.matplotlib/stylelib/` is listed in the output of `sys.path` (callable from ipython).
3. Test the notebook in the repo, or just invoke `matplotlib.pyplot.style.use('material_darker')`.


