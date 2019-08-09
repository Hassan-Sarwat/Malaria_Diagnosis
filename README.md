##### Machine Learning Nanodegree Capstone Project

Used transfer learning to train a model to diagnose malaria using images of cells, models used were inception v3, inception resnet and vgg19

### Steps to acquire data

- Download from https://ceb.nlm.nih.gov/proj/malaria/cell_images.zip
- extract zip file into input directory

Proposal review Link: https://review.udacity.com/#!/reviews/1894505

### Libraries used

- numpy
- cv2
- PIL
- Keras (needed to install weights)
- Sklearn
- tqdm
- Matplotlib

### Steps

1st of all, run practice, this will convert the images into a numpy array. This was mostly done because I couldnt read images and then train model in the same run due to lack of computing power

Then run either VGG19, IncResV2 or IncV3 depending on which model you want to observe

I've also included a file called Trial log, it has the parameters and the result of every model I tried

