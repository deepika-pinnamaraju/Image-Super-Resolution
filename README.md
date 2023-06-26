# Image-Super-Resolution


#### Overview of the Project:

I have selected image super resolution dataset from Kaggle site. The dataset contains high resolution and low resolution images. The project is about converting low resolution images into high resolution images using keras models. The project covers the following:

- Import required libraries
- Load the dataset from kaggle
- Visualizing the data and Displaying sample images with labels
- Slicing and Reshaping data/images into train,test and validation sets
- Defining and Implementing model(used batch normalization, dropout, learning rate optimization, epochs, kernel regularizers, functional API model, convolutional layers, activation and loss functions)
- Compiling the model
- Evaluating the model using test data
- Plotting accuracy/loss vs epochs
- Visualizing the predicted high resolution images
- Calculating PSNR(Peak Signal-to-Noise ratio) and SSIM(Structural Similarity Index) to get more insights about the quality and similarity of the generated high-resolution images compared to the true low-resolution images.
- Saving the models for future use when required
- Analyzing the results

#### Description of the data:

The dataset archive.zip which I have downloaded from Kaggle image super resolution has three folders: Raw data, train and val. But I am only going to use the Raw data which has two folders: high_res and low_res. I am latter splitting this data into train, test and validation sets.

high_res folder has 855 high resolution images and low_res folder has 855 low resolution images.

I want to convert 855 low resolution images into high resolution images.

#### Sample Images from the data

![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/0e7affa7-488f-4288-bcc5-c71fbd7e8aa2)
![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/64d35cbc-e7fd-414f-ba14-aa9da01ab5bf)
![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/e37aff4d-3d66-4070-befc-a4403b6b8de6)
![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/9889cd4d-3669-4e5b-9af0-429242dd5314)


#### Best model few prediction images

Sequential model:

![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/ab001acb-0ea2-4f53-b572-64498f610f8f)
![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/b31675f5-e7fc-46e8-9f78-58bbfc55061d)
![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/48fcbdba-829f-43a7-abf6-e55ee307c610)

#### Accuracy and loss vs epochs for best model

![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/ca514a96-09aa-4942-8cec-5e4d9efb926a)
![image](https://github.com/deepika-pinnamaraju/Image-Super-Resolution/assets/58209985/b212c893-7549-41f1-94a9-02e83f760d8a)


Best model of all is Sequential model with 68% accuracy, Structural similarity index(ssim) is 0.26 and Peak Signal-to-Noise Ratio(psnr) is 8.79.









