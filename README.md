# Simple computational chemistry pipeline in jupyter notebook

- Exercise for Spring school in comp chem 2019
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

- To deactivate the environment
```
source deactivate
```

- Install jupyter notebook
```
conda install jupyter
```

- To load the new environment in jupyter notebook, type in the following command (once the environment is activated). See [this](https://ipython.readthedocs.io/en/stable/install/kernel_install.html#kernels-for-different-environments) page for more info.
```
python -m ipykernel install --user --name my-rdkit-env --display-name "Python (my-rdkit-env)"
```