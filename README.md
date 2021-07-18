# AN ADVANCED APPROACH TO RECOGNIZE HUMAN ACTIVITIES VIA DEEP LEARNING
1. **[Datasets](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)**
2. **[Research Paper](https://github.com/Aryan05/test2.0/blob/main/Research%20Paper/243-248%2CTesma601%2CIJEAST.pdf)**

The study of wearable and handheld sensors recognizing human activity improved our understanding of human behaviours and human objectives.
Many academics seek to identify the activities of a user from raw data using the fewest necessary resources. In this article, we propose
a network of profound beliefs, a full-service architecture for the recognition of activities (DBN-LSTM). This DBN-LSTM method improves the
human predictability of raw data and reduces the complexity of the model as well as the requirement for comprehensive workmanship. A 
geographically and temporally rich network is CNN-LSTM. Our proposed model for the UCI HAR Public Data Set can achieve 99% accuracy 
and 92% precision.

### PROPOSED MODEL:
<img src="./Research Paper/ProposedModel.jpg" width = "2000" height = "500" align=center /> 

###  RESTRICTED BOLTZMANN MACHINE EQUATION
These are neural networks when they operate in an unsupervised or stochastic manner. According to Hinton [20], they can be used 
to reduce size, classify, correlate, and conduct regressions. In each RBM, there are two levels, one that is visible and another
that is hidden within the DBM. The two layers are connected and do not have connections within a layer. It is possible to determine 
the intrinsic relationship among binary data by usingthe properties of RBMs, whose energy functions are specified as follows:
<img src="./Research Paper/Equation.png" width = "300" height = "200" align=center />

### NEURAL NETWORK LAYERS:
These networks are made up of three neuronal units connected directly to their inputs. As a rule, there is a lesser number of
hidden units than visible ones. Encoding (compression) and reconstructing (reconstruction) are the two steps in the autoencoding 
process. We need to find the smallest error possible efficient way to represent the input data (i.e., a compact representation). 
DBN auto-encoders are models containing auto-encoder regression-based models that are used to create generative models for 
extracting features from encrypted data. Data vectors are usually stored in the last hidden layer. Moreover, auto-encoders are 
a general class of algorithms used to reduce the size of input data representations.

<img src="./Research Paper/Neural Network Layers.jpg" width = "300" height = "300" align=center />  <img src="./Research Paper/NetworkModel.jpg" width = "300" height = "190" align=center />

<img src="./HAR-CNN-Keras/Dataset.png" width = "300" height = "200" align=center />  

### Project Made by- Aryan Karn
