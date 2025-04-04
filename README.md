# GitHub Codespaces ♥️ Jupyter Notebooks

This is a fork of the original repo to fix bugs in the image classification notebook.

There is [documentation](https://docs.github.com/en/codespaces/developing-in-a-codespace/getting-started-with-github-codespaces-for-machine-learning) to accompany the repo.

When in the Codespace, select a Python 3.12 environment (which will install the requirements) and then run the following commands to fix some dependency issues.

```bash
pip uninstall torch torchvision
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu116
```
