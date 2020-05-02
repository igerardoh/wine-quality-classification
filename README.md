# wine-quality-classification

### Description
The dataset used on this classification model is the result of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines. This dataset was taken from the following website: [Wine recognition data](https://archive.ics.uci.edu/ml/datasets/wine)

##### Number of Features

1) Alcohol
2) Malic acid
3) Ash
4) Alcalinity of ash  
5) Magnesium
6) Total phenols
7) Flavanoids
8) Nonflavanoid phenols
9) Proanthocyanins
10) Color intensity
11) Hue
12) OD280/OD315 of diluted wines
13) Proline            

##### Classes

- class 1 : 59
- class 2 : 71
- class 3 : 48

### Dependencies
You can use `pip` or `conda` to install the dependencies:
- tensorflow
- matplotlib
- jupyter
- pandas
- seaborn
- scikit-learn

### Usage
If you want to try this program, download this repo and launch jupyter to run it on your machine. 

### - - - TODO  - - -

* ENVIRONMENT PREPARATION
    * ~~Install library dependencies~~
    * Document installation and usage


* DATA EXPLORATION
    * Add dataset description
    * ~~Preview the structure of the dataset~~
    * ~~Add data visualizations~~


* DATA PREPROCESSING
    * ~~Apply standarization to feature data~~
    * ~~Apply one-hot encoding to categorical data~~
    * ~~Split data into training and testing sets~~
    * Output preprocessed data for faster preloading


* DATA ANALYSIS
    * ~~Define network parameters~~
    * ~~Define network structure~~
    * ~~Add different network configurations~~
        * ~~Define learning rate with different decaying methods~~
        * ~~Set up cost, optimizer, and accuracy function with different configurations~~
    * ~~Define model execution~~
    * ~~Visualize evolution of MSE on training and testing datasets through epoch iteration~~
    * ~~Visualize evolution of loss function~~
    * ~~Visualize evolution of learning rate~~
    * Add log and summary writer
    * Add Tensorboard visualization
    * Add checkpoints for model restoration


* MODEL DEPLOYMENT
    * Load a pretrained model
    * Test it with new data


* OTHERS
    * Update README files
    * Update all nbviewer links
    * Add Tensorflow 1.x, Tensorflow 2.x, keras, tf.keras, and scikit-learn data analysis notebooks
