# DeepFake-Project
This project aims to detect deep fakes by using machine learning.

-Datasets saved in the zip.file can be found in the following link: https://drive.google.com/drive/folders/1mmRbFVWyHh1jcw7xiXbHah0Aam8thXph?usp=sharing
 There are two dataset: one contains FFHQ real images and fake images generated by StyleGAN, another one contains FFHQ real images and fake images generated by StyleGAN2.

-StyleGAN folder: https://drive.google.com/drive/folders/1yQu6NQP3UKx9IW485pumhKt72JGRePLV?usp=sharing
 The generated fake images are contained in the results file.
  
-StyleGAN2 folded used to generating fake imagesr: https://drive.google.com/drive/folders/1F1OliE13xqKbQLW3JIaQ78O80fBic4OT?usp=sharing
 The generated fake images are contained in the results file.
  
-generate_fake_images.ipynb is used to generate fake images by using StyleGAN and StyleGAN2.

-resize,_mean_and_std.ipynb is used to resize all images from size of 1024x1024 to size of 128x128 and calculate the mean and standard deviation of the training set.

-CIFAR10_ResNet18.ipynb and CIFAR_10_VGG.ipynb are used to classifying 10 classes in CIFAR-10 datasets by using two models.

-ResNet18-FFHQ-stylegan.ipynb and ResNet18-FFHQ-stylegan2.ipynb are used to classify two classes of each dataset by using ResNet18.

-VGG16-FFHQ-stylegan.ipynb and VGG16-FFHQ-stylegan2.ipynb are used to classify two classes of each dataset by using VGG16.

-Visualizing_featuremaps_ResNet18.ipynb is used to visualize the feature maps of one image passing through each block of ResNet18.

-1DDCT_2DDCT_HighComponents.ipynb is used to visualize the power spectrum and high frequency components of an image.

-DCT_FFHQ_Stylegan-LR.ipynb and DCT_FFHQ_Stylegan2-LR.ipynb are used to classify two classes of each dataset after DCT transform by using logistic regression.

-PCA_on_images.ipynb and PCA_on_DCT.ipynb are used to classify two classes of PCA componnets of dataset and dataset after DCT transform by using logistic regression.
