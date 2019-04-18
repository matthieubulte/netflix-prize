# Netflix Prize Data

Toying around with the Netflix Prize Dataset. I wanted to use this dataset to prototype movie recommendation, but realized after doing some visualization that the number of available features is simply too low to do the kind of modelling I wanted to do. This repository thus only contains code to pre-process and plot some intersting figures about the dataset.

### Getting the data
You can download the data used in this project from [Kaggle](https://www.kaggle.com/netflix-inc/netflix-prize-data/version/1). You should then extract the content of the zipped dataset in the `./dataset` directory.

### Installing
I used [anaconda](https://www.anaconda.com/) to manage my dependencies in this project. To re-create my environment, simply run `conda env create -n netflix -f environment.yml` and activate it using `conda activate netflix`.