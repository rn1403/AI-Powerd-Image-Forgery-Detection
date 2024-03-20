
# AI Powerd Image Forgery Detection

In this project, we used Tensorflow in order to implement a Convolutional Neural Network (CNN) for the purpose of extracting features in the problem of image forgery detection. Following the feature fusion, we take the extracted features and give them as input to an SVM that performs the final binary classification task. The SVM implementation was taken from scikit-learn. The datasets used in this project are the CASIA2 and the MICC-F2000 datasets. This study was conducted as a final project of Pune University's Electronics and Computer Engineering Programe in 2024 by Group id 1.

This project is aimed to detect various types of forgery in a image using deep learning model.
In this project I have implemented CNN, CNN-SVM and a novel **attention-based architecture** to intelligently analyze image content and identify potential forgeries. 
Here I have employed the RELU activation function in the CNN network to enhance the model's ability to capture complex patterns and features, contributing to the system's remarkable accuracy of 95%. 
## Authors

- [@rn1403](https://github.com/rn1403/)


## Network Architecure 

The CNN architecture of this project is shown in the image below. In the training phase, after the final convolution, a fully connected layer with softmax is applied. In the testing phase, the 400-D output of the final convolutional layer is used in the next Feature Fusion step that creates the feature vectors.

![image](https://github.com/rn1403/AI-Powerd-Image-Forgery-Detection/assets/122139909/c51727ed-b87e-4c2b-a236-e34b1f83ff11)


## Results

The accuracy and cross-entropy loss per epoch during the CNN training for the two datasets is shown below: 

![accuracy_Proposed](https://github.com/rn1403/AI-Powerd-Image-Forgery-Detection/assets/122139909/80ae925d-84b3-4a59-8c4c-215f40967b45) ![loss_Proposed](https://github.com/rn1403/AI-Powerd-Image-Forgery-Detection/assets/122139909/05e450d6-1f55-4d74-964f-10abf17d1474)



## Deployment

To run this project after downloading it

```bash
  python "image forgery detection.py"
```

