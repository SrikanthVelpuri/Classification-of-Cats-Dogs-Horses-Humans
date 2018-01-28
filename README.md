# Classification-of-Cats-Dogs-Horses-Humans

Using Transfer Learning method of Classification of four different classes (cats,Dogs,Horses,Human)



Data used here is custom data collected from internet.
  
  labels - full dataset
  
  ### convert class labels to one-hot encoding
  
  0 for cat - labels[0:202]
  
  1 for dog - labels[202:404]
  
  2 for horse - labels[404:606]
  
  3 for humans - labels[606:]
  
  Shuffling the dataset
   
  Spliting the dataset into train data(80%) and test data(20%) 
  
  

## Using VGG-16 model
  
  Testing of VGG16 model using random image.
  
  Summary of VGG-16 model.
  
  Using our own custom layers.
  
  Freezing all other layers except the last custom layer.
  
  Compiling the model with loss function='categorical_crossentropy',optimizer='rmsprop'
  
  Training data using random epochs and random batch sizes and choosing the best values.
  
  Validation accuracy: 98%
  
  Plotting training  loss vs epochs and training accuracy vs validation accuracy .
  
  
## Using RESNET-50 model
  
  Testing of RESNET-50 model using random image.
  
  Summary of RESNET-50 model.
  
  Using our own custom layers.
  
  Freezing all other layers except the last custom layer.
  
  Compiling the model with loss function='categorical_crossentropy',optimizer='adam'
  
  Training data using random epochs and random batch sizes and choosing the best values.
  
  Validation accuracy: 99%
  
  Plotting training  loss vs epochs and training accuracy vs validation accuracy .
  


