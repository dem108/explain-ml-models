# setup_conda

## how to

If it's the first time setting up conda in your bash environment,

```bash
conda init bash
```

Then,

```bash
conda create -n explain_ml python=3.6.*
conda activate explain_ml
pip install -r requirements.txt
```

If you want to use this conda environment as a Jupyter Kernel,

```bash
jupyter nbextension install --py --user azureml.widgets
jupyter nbextension enable azureml.widgets --user --py

ipython kernel install --user --name explain_ml --display-name "Python (explain_ml)"

```
