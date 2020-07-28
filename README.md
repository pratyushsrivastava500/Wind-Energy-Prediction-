# SBSPS-Challenge-451-Predicting-the-energy-output-of-wind-turbine-based-on-weather-condition
#Description:

#Dataset:

The dataset that is used in this model is download from  Kaggle - Scada Dataset

#Getting started

#Setting up environment

*Using Conda
conda env create --file environment.yml

*Using pip
Working on it...

#Running Notebook

*In your anaconda prompt cd to this repo and run the following

conda activate SmartInternz
jupyter notebook

#Known Issues

*AssertionError: Torch not compiled with CUDA enabled


Sometime installing torch from anaconda packages might cause this issue. To fix this download appropriate package from Pytorch. If you are using anaconda distribution and CUDA 10.2 use this command
conda install pytorch torchvision cudatoolkit=10.2 -c pytorch



*Complete Project Descritpion is in the Video Link given below
https://drive.google.com/file/d/1kzXenmSO950aUajp4pcQ8i0MORaL1jaj/view?usp=sharing
