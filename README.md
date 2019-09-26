# Landscape_classifier

This is a landscape classifier which classsifies the given landscape images into disaster or not disaster category.

Dataset:
I made the datset by myself using googleimagesdownload library. Or one could manually download the dataset from google images using this link: https://www.pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/

Libraries used: 
Fastai's vision library, open-cv, matplotlib

I have used transfer learning inorder to get more accurate results without exhausting a lot of computation resources. As in transfer learning, a pre-trained neural network is used.

We have used RESNET34 model which has given satisfactory result on a dataset of only about 300 images. 
Accuracy achieved is 79% approximately.

