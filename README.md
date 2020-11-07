# COMP7404 Group Project - xDeepFM for Recommender Systems

eXtreme Deep Factorization Machine ([xDeepFM](https://arxiv.org/abs/1803.05170))

This paper propose a novel Compressed Interaction Network (CIN), which aims to generate feature interactions in an explicit fashion and at the vector-wise level.

## Github Repository

[GitHub: xDeepFM_for_Recommender_Systems](https://github.com/pseudoyu/xDeepFM_for_Recommender_Systems)

## Video Demo

[Video Demo: xDeepFM_for_Recommender_Systems]()

## Datasets

1. **[Criteo Dataset](http://labs.criteo.com/2014/02/kaggle-display-advertising-challenge-dataset/).** It is a famous industry benchmarking dataset for developing models predicting ad click-through rate, and is publicly accessible. Given a user and the page he is visiting, the goal is to predict the probability that he will clik on a given ad

## Running Environment

I strongly recommmend that you use [Anaconda](https://www.anaconda.com) to implement this project. Here is some simple instructions:
1. Download a suitable version ([Windows](https://repo.anaconda.com/archive/Anaconda3-2020.07-Windows-x86_64.exe)/[MacOS](https://repo.anaconda.com/archive/Anaconda3-2020.07-MacOSX-x86_64.pkg)/[Linux](https://repo.anaconda.com/archive/Anaconda3-2020.07-Linux-x86_64.sh))  for your OS and install it (check for latest version from [Anaconda](https://www.anaconda.com))
   1. On Windows or MacOS, you can just use the *.exe* or *.pkg* installer and follow the instructions
   2. On Linux, you may need to run `bash ./.Anaconda3-2020.07-Linux-x86_64.sh` in the same directory of the downloaded *.sh* file to allow the installer to initialize Anaconda3 in your .bashrc
2. Create a dedicated Conda environment for this project (strongly recommended)
   1. Run `conda create -n xdeepfm python=3.6` and enter `y` to create the conda environment
   2. Run `conda activate xdeepfm` to activate the project environment
3. Run `pip install -r requirements.txt` to install the package dependencies
4. Now you can run the code simply through `python main.py`

### Dependencies
- absl-py==0.8.1
- astor==0.8.0
- gast==0.3.2
- google-pasta==0.1.7
- grpcio==1.24.3
- h5py==2.10.0
- joblib==0.14.0
- Keras-Applications==1.0.8
- Keras-Preprocessing==1.1.0
- Markdown==3.1.1
- numpy==1.17.3
- packaging==19.2
- protobuf==3.10.0
- pyparsing==2.4.2
- PyYAML==5.1.2
- scikit-learn==0.21.3
- scipy==1.3.1
- six==1.12.0
- sklearn==0.0
- tensorboard==1.14.0
- tensorflow==1.14.0
- tensorflow-estimator==1.14.0
- termcolor==1.1.0
- Werkzeug==0.16.0
- wrapt==1.11.2

## Running Results

### Running Example 1

### Running Example 2
