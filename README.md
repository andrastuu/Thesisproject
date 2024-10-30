This is where the codes for my Masters thesis project can be found

Abstract: The amount of astronomical data collected by different observatories 
has been exponentially increasing in recent years. Classifying the astronomical objects 
captured through different means is a crucial part of processing astronomical data. 
The thesis is aiming to contribute to the field of galaxy classification by advancing accuracy 
and understanding the interplay between data quality, model performance, 
and observational advancements. 
The datasets used are Galaxy10SDSS, Galaxy10DECals, and a sample of the Galaxy10DECals dataset, 
with high redshift. The methodology consists of preprocessing the images, 
with Supervised and Unsupervised Wiener Deconvolution, Chan-Vese segmentation, 
and Non-Local Means denoising. For the multi-class classification of the preprocessed 
and original images, CNN and ViT models are used. 
The preprocessing of the images generally in- creased the models’ performance. 
The best model in most cases was the ViT model, while for the high redshift sample, 
the CNN model performed better. The best preprocessing methods were 
Non-Local Means Denoising and Supervised Wiener Deconvolution. 
In the aspect of computational efficiency, 
the best preprocessing method was Supervised Wiener Deconvolution, 
while the ViT model was more efficient than the CNN.

