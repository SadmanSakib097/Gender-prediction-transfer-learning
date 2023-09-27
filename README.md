# Predicting-Gender-from-Human-or-Non-human-Social-Media-Profile-Photos-by-using-Transfer-Learning
In this study, we will predict gender using transfer learning models like VGG16, VGG19, and Alexnet and select the optimal model comparing the accuracy of these models on different datasets. Here it is a binary class classification problem as it contains 2 classes: 
male 
Female.

Here we create four datasets that contain different types of profile photos of males and females.
The four datasets are:
 Self-photo dataset.
 Group photo dataset.
 Celebrity photo dataset.
 Other photo dataset.

➤In the dataset (Self Photo), we collect self-photos that are used as profile photos on various social media platforms such as Facebook, Instagram, and Twitter by both male and female users. When collecting data, we observed a pattern in which females use self-photo as profile photos and show various facial expressions than males.

➤In the dataset (Group photo), we collect group photos that are used as profile photos on various social media platforms such as Facebook, Instagram, and Twitter by both male and female users. When collecting group photos, we discovered a pattern in which users use group photos of special occasions such as weddings, birthday parties, memorable incidents with loved ones, or sporting events.

➤In the dataset (Celebrity photo), we collect celebrity photos that are used by both male and female users as profile photos on various social media platforms.

➤In dataset (Other photo), mainly contains photos of cartoons, birds, animals, flowers, movie characters, self-cartoon faces, unique logos, and so on that are used as profile photos by social media users both male and female.

Installing necessary software and files:

In order to run smoothly,  Computer Vision programs use some software and files. For this, we first need to install Python, Jupyter notebook, and Tensorflow. Then we complete all Python and Tensorflow implementations on the Jupyter notebook. We use the free Anaconda version to run Jupyter Notebook and run other applications and files.

Link to Download Anaconda:
https://www.anaconda.com/products/distribution

Link to download Jupyter using Anaconda:
https://jupyter.org/install

Link to download TensorFlow:
https://www.tensorflow.org/install/source#gpu



Installing Python libraries and packages:
Install some essential python libraries and packages for image processing.
Pillow/PIL
NumPy
Pandas etc
Matplotlib
Using the pip command we install these libraries in jupyter notebook.

Photo Processing:
We apply multiple pre-processing and normalization techniques to obtain better accuracy.
Cropping
Resize 
Normalize

 
 
Data Augmentation:
It is a method of artificially increasing data volume by generating new data points from existing data. Every dataset is subjected to geometric transformations. There are several techniques available, including flipping, rotation, shearing, cropping, and translation. In our study, we use three types of augmentation techniques:

Translations.
Flipping.
Rotation.

