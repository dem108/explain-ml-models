# Explain ML Models

This repo tries some approaches to explain machine learning models.

## How to

1. Edit `setup-workspace.py`: use your preferred names for AML workspace, resource group etc. Update AML compute cluster info if needed.

1. Follow README_AML.md. If you do not want to set up GitHub Actions, just finish the first 2 steps: running `setup-workspace.py`. Creation of workspace will not take too long.

1. Set up and activate conda env by following `setup_conda.md`.

1. Choose the conda env from your IDE. If you're using VSCode or Codespaces, you may want to reopen or refresh the window.

1. Open [AML studio](https://ml.azure.com) and locate your workspace.

1. Check out [notebooks](notebooks) and edit accordingly.

## Resources

* [AzureML Template](https://github.com/Azure/azureml-template)

* [Blackbox model explanation example](https://github.com/interpretml/interpret/blob/develop/examples/python/notebooks/Explaining%20Blackbox%20Classifiers.ipynb)
