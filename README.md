# VGG16-with-TensorflowJs
i have used a tensorflowJs with pretrained model VGG16 and Mobilenet 
## How to use it efficiently
  In this repo. i haven't added vgg16 but we can download it by using following two to three lines of command.
 - 1. import keras 
 - 2. import tensorflowjs as TFJS
 - // for downloading the vgg16 model u have to add following command
 - 3. vgg16 = keras.applications.vgg16.VGG16()
 - 4. tfjs.converters.save_keras_model(vgg16, path to views or client folder in your app)
 - // this will load your model into the particular directory and create a shards of files...and now u can refer other files to run into your    machine
  

