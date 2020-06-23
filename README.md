# jupyterlab-favorites

Add the ability to save favorite folders to JupyterLab for quicker browsing

## Prerequisites

* JupyterLab
* For development, an active `conda` environment with `nodejs`

## Installation

```{bash}
jupyter labextension install jupyterlab-favorites
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
npm run build
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

## Legacy Jupyterlab v1 Support

Via NPM:
```{bash}
jupyter labextension install jupyterlab-favorites@1.0.0
```

Or use the tagged 1.0.0 release at:
https://github.com/NERSC/jupyterlab-favorites/tree/v1.0.0
