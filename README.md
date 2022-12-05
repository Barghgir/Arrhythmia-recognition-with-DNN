# Arrhythmia-recognition-with-DNN
Arrhythmia Recognition with keras

The shape of model is:

Layer (type)---------------------Output Shape--------------Param 

dense_18 (Dense)----------------(None, 720, 100)------------200       

dropout_17 (Dropout)------------(None, 720, 100)------------0         

conv1d_36 (Conv1D)--------------(None, 711, 100)------------100100    

conv1d_37 (Conv1D)--------------(None, 702, 100)------------100100    

max_pooling1d_9 (MaxPooling1)---(None, 234, 100)------------0         

conv1d_38 (Conv1D)--------------(None, 225, 160)------------160160    

conv1d_39 (Conv1D)--------------(None, 216, 160)------------256160    

global_average_pooling1d_9 -----(None, 160)-----------------0         

dropout_18 (Dropout)------------(None, 160)-----------------0         

dense_19 (Dense)----------------(None, 1)-------------------161       


