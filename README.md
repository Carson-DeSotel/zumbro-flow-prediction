# zumbro-flow-prediction

zumbro-flow-prediction is a series of Jupyter Notebooks that import and process a variety of environmental data to create a machine learning model that predicts streamflow based on 10 years of streamflow data for the South Fork Zumbro River near Rochester, MN.

## Authors & Contact Information

- Carson DeSotel (desot033@umn.edu, carson.desotel@gmail.com) 
- Martha Burket (burke781@umn.edu, martha.burket@gmail.com)

Please reach out to either author if any concerns arise.

## Installation & Usage

The project is built in Jupyter Notebooks. If you want to modify / run these Notebooks on your own machine, please visit [Jupyter's Installation page](https://jupyter.org/install) for information on how to install Jupyter on your own machine. 

Please also ensure that you're using Python 3 which can be downloaded [here](https://www.python.org/downloads/).

This project also uses ```pip``` to manage package installation. ```pip``` can be downloaded from [here](https://pip.pypa.io/en/stable/installation/).

Once the basic software has been installed, this project can be downloaded through cloning the git repository.

```bash
git clone https://github.com/Carson-DeSotel/zumbro-flow-prediction.git
```

or by downloading the .zip file from the [GitHub repo](https://github.com/Carson-DeSotel/zumbro-flow-prediction).

## Downloading Data

A large part of the data used in this project is handled through .csv files that have been pre-processed and are parts of the GitHub repo. Data required for ```watershed-delineation-land-use.ipynb``` is too large to be handled through GitHub, so extra downloading must be done. 

Please download further required data from [this Google Drive folder](https://drive.google.com/drive/folders/1cq252tFyw-nanUq_Bzm3mbWvqUURr8qt?usp=sharing) and export the files to the ```data/``` folder in your local repository.

## Contribution
Ideally, this project should remain closed to change. Its goal is to be a proof of concept for a potential ML model that can be applied to streams. 

Contact Carson DeSotel if you'd like to modify the code. 