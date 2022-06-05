# DNN-over-Unlabelled-data


Based on a small labelled and large unlabeled training set, the system will predict agency and sociality for happy moments in the test set. 
- Agency label (0 or 1, where 1 indicates that the individual who created the text was actively participating as an agent) and 
- social label will be the classes to forecast for each text (0 or 1, where 1 means that the text describes a social activity).

Data Used - https://github.com/kj2013/claff-happydb

Files Description 
- EDA on the TRAIN and TEST Data Set.ipynb : “Pre-processing TRAIN and TEST data” and store the resultant using ‘Pickle’.
- Baseline Classifier.ipynb : Both the labels (social, agency) were individually classified using "Stochastic Gradient Descent (SGD)", "Logistic Regression", "Linear SVC", "Random Forest", "K-Nearest Neignours", "Hyper tuned Stochastic Gradient Descent (SGD) Model" and "Hyper tuned Logistic Regression Model".


     ![image](https://user-images.githubusercontent.com/97570090/172061510-d8e9d7b4-b2e6-4cb6-bb56-ed5a93ea51af.png)


- DL Model (LSTM and Bi-Directional LSTM).ipynb: Create the LSTM network's architecture, LSTM model with Embedding layer, LSTM layer and Dense layer with a single unit, Bi-directional LSTM model with Glove Embedding layer and 2 LSTM layer and Dense Layer.
- DL-CNNmodel.ipynb : Built Keras Model, Sequential model + Keras Embedding Layer, Sequential model + Keras Embedding Layer/Glove Embedding Layer + GlobalMaxPooling1D layer + CNN.
- Deep NeuralNetworks.ipynb : Sequential model (3 layers) and Sequential model (3 layers).
