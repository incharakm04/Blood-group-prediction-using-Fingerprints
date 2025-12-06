# Blood-group-prediction-using-Fingerprints
This project uses Convolutional Neural Networks (CNN) and Transfer Learning with ResNet50 to predict a person's blood group based on their fingerprint image.
Fingerprint patterns contain ridge-level and minutiae features that can be mapped to biological traits — including blood groups.

This model learns such patterns and classifies images into blood groups like:

A+

A-

B+

B-

AB+

AB-

O+

O-

🚀 Features

✔ Predict blood group from fingerprint images
✔ Uses powerful pretrained ResNet50 for feature extraction
✔ Custom CNN layers for classification
✔ Image preprocessing with augmentation
✔ Model evaluation and classification report
✔ Single-image prediction with confidence score
✔ Well-structured training + testing pipeline

Folder Structure

blood_group_prediction/

│── data/

│   ├── train/

│   │    ├── A+/

│   │    ├── B+/

│   │    ├── ...

│   ├── test/

│       ├── A+/

│       ├── B+/

│       ├── ...

├── BloodGroup_ResNet50.ipynb

│

│── README.md

│── requirements.txt
