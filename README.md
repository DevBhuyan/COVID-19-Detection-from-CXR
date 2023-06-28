# COVID-19-Detection-from-CXR
Images of Chest X-Rays
Processed by CLAHE (Contrast Limiting Adaptive Histogram Equalization)
Prepared Dataset: https://drive.google.com/drive/folders/1S33YkmiOx3uDBzWrBUhX7RNWIR75YIR_?usp=sharing
250 training images each for 4 classes: COVID-19, BACTERIAL PNEUMONIA, VIRAL PNEUMONIA, NORMAL
50 testing images each for 4 classes: COVID-19, BACTERIAL PNEUMONIA, VIRAL PNEUMONIA, NORMAL

This is an attempt to Predict Covid-19 from Chest X-Ray images using Transfer Learning networks such as Inceptionv3, VGG-19, etc.
This project is based on the paper: https://onlinelibrary.wiley.com/doi/full/10.1111/exsy.12749

The hyperparameters are tuned to the precise use-case. These were found to be optimal after extensive experimentation. Feel free to experiment. To test any network, simply download the corresponding ipynb file and change the input directory to your dataset directory and run it as a Jupyter notebook.
