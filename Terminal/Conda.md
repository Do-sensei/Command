# basic

- Verify conda is installed, check version number
```shell
$ conda info
$ conda info -envs
```

- Update 
	- 1. conda to the current version
	- 2. any installed program
```shell
$ conda update conda
$ conda update <PACKAGENAME>
```

- Install a package included in Anaconda
```shell
$ conda install <PACKAGENAME>
$ pip install <PACKAGENAME>
```

# Using  environment

- Create a new enviroment named 'NAME', install Python 3.X
```shell
$ conda create --name NAME python=3.X
```

- list of all my enviroments
```shell
$ conda env list
```

- List all packages and versions installed in active environment
```Shell
$ conda list
```

# Activate and deactivate

```shell
$ conda activate <EVIRONMENT_NAME>
$ conda deactivate
```
> Activate your <EVIRONMENT_NAME>