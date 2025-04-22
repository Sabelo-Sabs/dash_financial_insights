# Environment Setup

## Installation with Anaconda/Miniconda

Run the two commands from the root directory.

```bash
# Create the environment from your YAML
conda env create -f ./environment/conda.yaml

# (First‑time only) initialize Conda for your shell and restart it
source ~/.bashrc   # or ~/.zshrc, ~/.config/fish/config.fish, etc.

# Activate your new environment
conda activate dash-app-tutorial

```


## Installation with Pip

**Note:** Python >= 3.9 is required to use the [modern style](https://peps.python.org/pep-0585/) of type annotations.

Run the command from the root directory.

```shell
python -m pip install -r ./environment/requirements.txt
```