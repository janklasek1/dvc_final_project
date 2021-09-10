# Installation

## Installation on _Windows_

### Install with choco
- The easiest way to install from command line for most cases is to install Chocolatey on your machine, and use the choco command:

 $ choco install dvc

### Install with conda
- You can use conda from Anaconda Prompt, a POSIX-like command line terminal in Windows.

 - Installs much faster than conda

 $ conda install -c conda-forge mamba

 $ mamba install -c conda-forge dvc

- Depending on the type of the remote storage you plan to use, you might need to install optional dependencies: dvc-s3, dvc-azure, dvc-gdrive, dvc-gs, dvc-oss, dvc-ssh.

### Install with pip
- From Command Prompt or other recommended consoles:

 $ pip install dvc

- Depending on the type of the remote storage you plan to use, you might need to install optional dependencies: [s3], [azure], [gdrive], [gs], [oss], [ssh]. Use [all] to include them all

### Windows installer

- An easy way is to use the self-contained, executable installer (binary), which is available from the big "Download" button on the home page. You can also get it from the release page on GitHub.

- You'll need to download and run the installer again each time you want to update DVC. You may use Windows Uninstaller to remove the program.

> Note that this method by default enables symlink permissions for all users, so they can use them to optimize DVC operations.

## Install with _macOS_
>To use DVC as a Python library, please install with pip or with conda.

### Install with brew

 $ brew install dvc

### Install from package

- Get the PKG (binary) from the big "Download" button on the home page, or from the release page on GitHub.

### Install with pip
- We strongly recommend creating a virtual environment or using pipx (on Python 3.6+) to encapsulate your local environment.

$ pip install dvc

- Depending on the type of the remote storage you plan to use, you might need to install optional dependencies: [s3], [azure], [gdrive], [gs], [oss], [ssh]. Use [all] to include them all.

### Install with conda

- Installs much faster than conda

$ conda install -c conda-forge mamba  onda install -c conda-forge mamba

$ mamba install -c conda-forge dvc

- Depending on the type of the remote storage you plan to use, you might need to install optional dependencies: dvc-s3, dvc-azure, dvc-gdrive, dvc-gs, dvc-oss, dvc-ssh.
