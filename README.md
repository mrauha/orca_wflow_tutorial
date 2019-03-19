# Simple computational chemistry pipeline in jupyter notebook

- Exercise for SSCC-19
- Markus Rauhalahti, markus.rauhalahti@helsinki.fi, mrauha.github.io


## Setting up
- Create a new conda environment with rdkit installed

```
conda create -c rdkit -n my-rdkit-env rdkit
```

- To activate it, the left part of your terminal should read (my-rdkit-env) afterwards
```
source activate my-rdkit-env
```
- (To deactivate the environment type `source deactivate`)

- Install jupyter notebook and some other libraries to the environment
```
conda install jupyter
conda install matplotlib
pip install deepdish
```

- To load the new environment in jupyter notebook, type in the following command (once the environment is activated). See [this](https://ipython.readthedocs.io/en/stable/install/kernel_install.html#kernels-for-different-environments) page for more info.
```
python -m ipykernel install --user --name my-rdkit-env --display-name "Python (my-rdkit-env)"
```
