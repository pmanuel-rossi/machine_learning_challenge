# machine_learning_challenge

All the models that I chose are based in the DNN type of models from Keras, what i decided to vary is the input of the data and the tweaking of the parameters for each model. 

## 7 columns model

The first model that I chose is based on 7 columns as input, and 2 dense layers, resulting in 553 trainable parameters resulted with a 50 node layer and a 3 node layer for the output.

The result from this model is an accuracy of 80% predictability, I think that scaling the data differently and adding one more node layer would help with the result.

With the hiperparameter grid tunning, I added two 100 node layers before the output layer, generated 6 batch sizes for sampling and 3 different epochs.

The best grid model resulted beeing the one with the highest batch size and epochs resulting in 87% predictability, I will be adding more fine tunned steps on batch sizes and epochs in the next model. 

