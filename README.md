# Course pharmacokinetic/ pharmacodynamic modelling
This repository contains the pharmacokinetic/pharmacodynamic modelling course of the [König Systems Medicine of Liver Lab](https://livermetabolism.com). 
The project was developed as a teaching project as part of the Digital Health Professions Educator Program ah the Charité Berlin in 2024-2025.

![König lab](./images/banner.png)

# Installation

# uv
Using uv available from https://docs.astral.sh/uv/getting-started/installation/.
Create a virtual environment and synchronize the dependencies
```bash
uv venv
uv sync
```
This creates the `dhpe-pkpd` environment in `.venv`.

Using uv with Jupyter (https://docs.astral.sh/uv/guides/integration/jupyter/):
Create a kernel for the virtual environment
```bash
uv add --dev ipykernel
uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=dhpe-pkpd
```

Start jupyter lab
```bash
uv run --with jupyter jupyter lab
```


© 2024-2025 [Matthias König](https://livermetabolism.com)
