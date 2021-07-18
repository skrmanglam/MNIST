# MNIST
My Hello World to deep learning


Updating it with MNIST- Hand written digits
Used MNIST data base from tensor_flow database. 
## Used Tensorflow and Keras
Stats:
4ms/step - loss: 0.0598 - sparse_categorical_accuracy: 0.9830 - val_loss: 0.0804 - val_sparse_categorical_accuracy: 0.9753

*****************************************************************************************************************************************************************
Updated on Jul 14:
CNN with improved accuracy
Accuracy on test dataset: 0.9036999940872192
*****************************************************************************************************************************************************************
Added Cats and Dog classifier using CNNs
Model Stats:
Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d (Conv2D)              (None, 148, 148, 32)      896       
_________________________________________________________________
max_pooling2d (MaxPooling2D) (None, 74, 74, 32)        0         
_________________________________________________________________
conv2d_1 (Conv2D)            (None, 72, 72, 64)        18496     
_________________________________________________________________
max_pooling2d_1 (MaxPooling2 (None, 36, 36, 64)        0         
_________________________________________________________________
conv2d_2 (Conv2D)            (None, 34, 34, 128)       73856     
_________________________________________________________________
max_pooling2d_2 (MaxPooling2 (None, 17, 17, 128)       0         
_________________________________________________________________
conv2d_3 (Conv2D)            (None, 15, 15, 128)       147584    
_________________________________________________________________
max_pooling2d_3 (MaxPooling2 (None, 7, 7, 128)         0         
_________________________________________________________________
flatten (Flatten)            (None, 6272)              0         
_________________________________________________________________
dense (Dense)                (None, 512)               3211776   
_________________________________________________________________
dense_1 (Dense)              (None, 2)                 1026      
=================================================================
Total params: 3,453,634
Trainable params: 3,453,634
Non-trainable params: 0

![image](https://user-images.githubusercontent.com/31559064/126058690-fbececb9-ca60-4c82-8cd9-4ce784377390.png)
Model shows Overfitting.
