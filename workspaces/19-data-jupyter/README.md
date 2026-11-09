# Notebooks and data

Interactive notebooks for exploring data.

## What is already installed

- Python 3.12
- JupyterLab
- polars

## How to start

1. Open this folder in Visual Studio Code.
2. When it asks, choose **Reopen in Container**.
3. Wait for the setup to finish. This happens only the first time.

## First command to try

```
jupyter lab --ip=0.0.0.0
```

## Using it as a GitHub Codespace

GitHub only reads the `.devcontainer` folder at the top of the project,
so to use this recipe there, copy this folder's `devcontainer.json` into
a `.devcontainer` folder at the top of your own project.

## Files in this folder

- `devcontainer.json` - the recipe that builds the workspace.
- `README.md` - this instruction sheet.
