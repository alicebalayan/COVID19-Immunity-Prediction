# Data mining #

## Important stuff ##
* [Resources](./Resources.md)

## Notebook Setup ##
Use one of the following to be able to get an environment for jupyter.

### Anaconda (Recommended) ###
Follow [the official
guide](https://docs.anaconda.com/anaconda/user-guide/getting-started/)

### Docker ###
If you have docker installed, you can just run the following to get
jupyter and other data science tools ready
```shell
docker run -p 8888:8888 -v $PWD:/home/jovyan/work jupyter/scipy-notebook
```
Afterwards you should be able to see a link to your localhost; copy
and paste that in your browser, enter `work` and make changes.
