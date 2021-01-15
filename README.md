# CarND-Term1 Remote Container

> Create and open [CarND-Term1](https://github.com/udacity/CarND-Term1-Starter-Kit/) in a remote container in VSCode without messing up your local machine.

## Pre-reqs

- Docker
- VSCode
- [VSCode Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extensions

## How to set up

1. In VSCode, open the command pallete, search and select `Remote-Containers: Open folder in container...`, and select the current (this) folder.

2. Your working directory is the `/src` folder. In VSCode, open a new terminal and execute `/run.sh`, which will activate the conda environment and opens a jupyter notebook in the background.

3. VSCode will prompt you, at the bottom right, that some port is used (probably `8889`). You can click on the given link which opens a Jupyter notebook. Copy and paste the token from the terminal and log into the notebook.

4. Now, we are good to go.
