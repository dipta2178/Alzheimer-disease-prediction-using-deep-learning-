# Alzheimer-disease-prediction-using-deep-learning-

Using DenseNet-169 pretrained keras weights, the CNN model can classify Alzeimer's disease in a patient.

Dataset:  https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images

The DenseNet design clearly distinguishes between information that is maintained and information that is introduced to the network. DenseNet layers are 
relatively tiny, contributing just a small number of feature-maps to the network's "collective knowledge," while maintaining the integrity of the remaining feature-maps. The final classifier bases its judgment on the network's whole collection of feature-maps. In addition to having superior parameter efficiency, DenseNets also have enhanced information flow and gradients across the network, making them simple to train. There is an implied deep supervision since each layer has direct access to the gradients from the loss function and the original input signal. Deeper network architecture training is made easier as a result. Moreover, we see that dense connections have a regularizing impact that lessens overfitting on tasks with smaller training set sizes.

DenseNets utilize the network's potential through feature reuse rather than deriving representational power from exceptionally deep or broad architectures, producing condensed models that are simple to train and have a high parameter efficiency. The input of succeeding layers is more varied and more effective when feature-maps from several levels are combined. This is a significant distinction between DenseNets and ResNets. DenseNets are more straightforward and effective than Inception networks, which combine features from several layers as well.
