# audioMLalgorithms

This repository contains Machine Learning and Deep Learning algorithms and models (music information retrieval, features extraction, classification et similia) for audio applications. There are various folders, specifically:

- **DL-audio-classical-instrument-classifier**: algorithm for audio feature extraction and classification of classical musical **instrument** (violin, clarinet, cello ...) using a combination of Machine Learning (Support Vector Machines, K-Nearest Neighbours) and Deep Learning (Multi-Layer Perceptron) techniques and the Essentia library.

- **DL-audio-instrument-material-classifier**: algorithm for audio feature extraction and classification of classical musical instrument construction **material** (wood, plastic, metal ...) using a combination of Machine Learning (Support Vector Machines, K-Nearest Neighbours) and Deep Learning (Multi-Layer Perceptron) techniques and the Essentia library.

- **DL-music-genre-classifier**:  algorithm for music **genre** classification of audio samples using a combination of Machine Learning (Logistic Regression, Support Vector Machines) and Deep Learning (Multi-Layer Perceptron Classifier) techniques.

#

## DL-audio-classical-instrument-classifier


### Summary

The model was developed using a combination of Machine Learning (Support Vector Machine, K-Nearest Neighbours) and Deep Learning (Multilayer perceptron) techniques for feature extraction and classification.
The project is divided into three parts: feature extraction, classification and visualisation. The python jupyter notebook is located in the 'notebooks' folder. Feature extraction is performed using the Essentia library (open-source C++ library for audio analysis and audio-based music information retrieval) and Support Vector Machines. An initial classification is performed using neural networks (Multilayer Perceptron), followed by a second classification (K-Nearest Neighbours) and data visualisation.


### Dataset

The dataset used for this project is GoodSounds Dataset from Pompeu Fabra University (Barcelona, Spain). [Here](https://www.upf.edu/web/mtg/good-sounds) you can find more information on this dataset.

### Credits

This project was developed as part of the 'Music Information Retrieval' [course](https://www.upf.edu/web/smc/music-information-retrieval) of the master's programme 'Sound and Music Computing' at Pompeu Fabra University (Barcelona, Spain).


#

## DL-audio-instrument-material-classifier

### Summary

The model was developed using a combination of Machine Learning (Support Vector Machine, K-Nearest Neighbours) and Deep Learning (Multilayer perceptron) techniques for feature extraction and classification.
The project is divided into three parts: feature extraction, classification and visualisation. In the 'notebooks' folder are two python jupyter notebooks: 

1) In 'feature_extraction_MLP.ipynb' feature extraction is performed using the Essentia library (open-source C++ library for audio analysis and audio-based music information retrieval) and SVM. An initial classification is performed using neural networks (Multilayer Perceptron).

2) In "classification_visualisation_KNN" a second classification (K-Nearest Neighbours) and visualisation of the data is performed.


### Dataset

The dataset used for this project is GoodSounds Dataset from Pompeu Fabra University (Barcelona, Spain). [Here](https://www.upf.edu/web/mtg/good-sounds) you can find more information on this dataset.

### Credits

This project was developed as part of the 'Music Information Retrieval' [course](https://www.upf.edu/web/smc/music-information-retrieval) of the master's programme 'Sound and Music Computing' at Pompeu Fabra University (Barcelona, Spain).



#

## DL-music-genre-classifier

### Summary

The model was developed using a combination of Machine Learning (Support Vector Machine, Logistic Regression) and Deep Learning (Multi-Layer perceptron) techniques for music genre classification.
The project is divided into three parts: 



. In the 'notebooks' folder are three python jupyter notebooks: 

1) 

2) 

3)

1. Classifier implementation with scikit-learn notebook

Logistic Regression, Support Vector Machines and Multi Layer Perceptron with a pipeline to structure categorical and numerical data.

2. Some more classification tests notebook

This is a previous iteration than (1.), it shows other preprocessing pipelines that are probably less efficient and more prone to error.

3. Some tests with Keras notebook

Testing the classification using Keras, experiment with models, loss functions and metrics.
### Credits

This project was developed as part of the 'Advance Topics in Sound and Music Computing' [course](https://www.upf.edu/web/smc/advance-topics-in-smc) of the master's programme 'Sound and Music Computing' at Pompeu Fabra University (Barcelona, Spain).


