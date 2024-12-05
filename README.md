# Brain-Tumor-Detection
 
Main purpose of this project is to build a robust AI model that can classify if the patient has brain tumor or not 
based on the MRI images with an acceptable accuracy rate for medical applications.

However, acquiring a big enough dataset required to get the intended accuracy is a challenge in itself since Brain MRI images of cancer patients are hard to find 
publicly.

Therefore to solve the stated problem, we use DCGAN (Deep convolutional GAN) to create a synthetic dataset and then merge it with a robust classification
algorithm to predict the presence of tumor in a Brain MRI image.

The DCGAN mdoel is tuned extensively to create proper synthetic images by analysing and configuring the network and comapring the generated images with the real ones.
This is done by the algorithm using two essential components, 'Generator' and 'Discriminator'.