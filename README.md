# jupyterlab-mp4

A JupyterLab extension for rendering mp4 files.

## Prerequisites

- JupyterLab

## Installation

```bash
# if/when published
pip install jupyterlab_mp4

# else git clone repo and install locally from repo root folder
jlpm run build:prod
pip install .
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```
