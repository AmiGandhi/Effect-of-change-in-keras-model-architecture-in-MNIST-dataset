# Hyperparameter-Tuning-in-MNIST-dataset-using-Keras

  ## MODEL 1

  ** Test loss: 0.02603
  Test accuracy: 0.9924**

  conv2D (32)
  conv2D (64)
  MaxPooling2D()
  Dropout(0.25)
  Flatten()
  Dense(128)
  Dropout(0.5)
  Dense(num_classes,
  activation='softmax')
  
  
  ## MODEL 2

  **Test loss: 0.02729 
  Test accuracy: 0.9917**

  conv2D (32)
  conv2D (64)
  MaxPooling2D()
  **Dropout(0.50)**
  Flatten()
  Dense(128)
  Dropout(0.5)
  Dense(num_classes,
  activation='softmax')
  
  
  ## MODEL 3

  **Test loss: 0.0219 
  Test accuracy: 0.9928**

  conv2D (32)
  **conv2D (64)
  conv2D (64)**
  conv2D (64)
  MaxPooling2D()
  Dropout(0.25)
  Flatten()
  Dense(128)
  Dropout(0.5)
  Dense(num_classes,
  activation='softmax')
  
  
  ## MODEL 4

  **Test loss: 0.0196 
  Test accuracy: 0.9945**
  
  conv2D (32)
  conv2D (64)
  **MaxPooling2D()
  Dropout(0.25)
  conv2D (80)
  MaxPooling2D()**
  Dropout(0.25)
  Flatten()
  Dense(128)
  Dropout(0.5)
  Dense(num_classes,
  activation='softmax')
  
  
  ## MODEL 5

  **Test loss: 0.0222
  Test accuracy: 0.9941**
  
  conv2D (32)
  **conv2D (64)**
  conv2D (64)
  MaxPooling2D()
  Dropout(0.25)
  **conv2D (80)**
  conv2D (80)
  MaxPooling2D()
  Dropout(0.25)
  Flatten()
  Dense(128)
  Dropout(0.25)
  Dense(num_classes,
  activation='softmax')
  
