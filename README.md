# Different types of python-environment

## Project Based Environments[Env files are stored in project folder]

### 1: venv -> Python Pre-installed environment

```bash
# Creating virtual environment in windows
python -m env env_name

# Activating environment in Windows
env_name\Scripts\activate

# Activating environment in Linux
source env_name/bin/activate

# Deactivating environment
deactivate

```

### 2: virtualenv Environment

```bash
# Installation in windows
pip install virtualenv

# Creating virtual environment
virtualenv env_name

# Activating environment in Windows
env_name\Scripts\activate

# Activating environment in Linux
source env_name/bin/activate

# Deactivating environment in Windows
deactivate

```


## Package Based Environment[Env files are stored in package installed folder]

### 3: virtualenvwrapper-win Environment

```bash
# Installation in windows
pip install virtualenvwrapper-win

# Creating virtual environment in windows
mkvirtualenv env_name

# Activating environment in Linux
source env_name/bin/activate

# Deactivating environment
deactivate

```

### 4: Conda Environment

```bash

# Creating virtual environment in windows
conda.bat create --name env_name

# Activaiting environment in windows
conda.bat activate env_name

# Deactivating environment

# Removing environment in windows
conda.bat env remove -n env_name

# Installing package without activating the conda env => eg: C:\Users\ACER>
conda.bat env create -n env_name python=3.9 jupter pandas django

```
