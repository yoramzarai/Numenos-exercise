# TRUST4 Exercise for Numenos

This repository contains the Numenos exercise files. It is based on the [TRUS4 github](https://github.com/liulab-dfci/TRUST4), with additional files based on Numenos exercise requirement document, which is in the `./Docs` sub-folder.

## Notebook
The exercise notebook is [main_exercise.ipynb](https://github.com/yoramzarai/Numenos-exercise/blob/main/main_exercise.ipynb). It contains all the implementation code and descriptions. Please consult the notebook for a detailed description of the exercise.

## Data
The data is omitted here due to its size. Either contact me to request the data, or follow the descriptions in the notebook to download the data from its source.

## Results
Result figures are available in the `./Figure` folder. Results summary is available in the `Results Summary` section.

## Prerequisite
Before running the notebok, make sure that the following are installed in your system:
- perl5
- docker
- [uv](https://docs.astral.sh/uv/)

## Python
Python >=3.13 is used. Python environment is managed by [uv](https://docs.astral.sh/uv/). See the `pyproject.toml` file.

To create the virtual environment, simply install uv, clone this repository and execute:
```console
uv sync
```
This will create the virtual environment in the `./.venv` folder.

## TRUST4
For information about TRUST4, see the [TRUST4 github](https://github.com/liulab-dfci/TRUST4).
