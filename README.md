# Brain-Tumor-detection-using-Deep-Learning
This project describes how to use deep learning (CNN) to detect brain tumor in medical images, solving the problem of tumor differentiation and unraveling the complexity of the distributed grid. Four prominent CNN architectures and two additional models (MobileNet) are assessed for their performance in brain tumor classification. The research employs a varied dataset of brain MRI scans, incorporating different tumor types, sizes, and locations. Pre-processing techniques, such as image normalization and augmentation, enhance model robustness. Each CNN is fine-tuned and trained, with experiments evaluating accuracy, sensitivity, specificity, and computational efficiency. The comparative analysis identifies strengths and weaknesses, providing insights into the models' suitability for real-world clinical applications. 

# Introduction
Brain tumor is a complex and diverse class of medical conditions, pose a significant challenge in the field of healthcare due to their varied characteristics and potential negative effects on human well-being. These abnormal growths within the brain can manifest in diverse sizes, shapes, and locations, making their search and classification are important tasks in medical analysis.[1]
Identification and classification of brain tumors when done manually is not only time-consuming but can lead to inaccurate results, emphasizing the need for advanced technologies to enhance diagnostic precision. The application of Deep Learning techniques, especially CNNs, show great promise in detecting of brain tumors medical images, notably Magnetic Resonance Imaging (MRI) scans. [2]
In this research endeavor, we focus on four prominent CNN architectures: ResNet-50, Mobile-Net,VGG-16, DenseNet-121, and Inception V3. [3] Each of the above models represents a unique approach to extract features and classify problem, contributing to the evolving landscape of deep learning applications in medical imaging

1- VGG-16 (Visual Geometry Group 16): VGG-16 is characterized by its deep architecture with 16 weight layers. It is renowned for its simplicity and uniformity, employing 3x3 convolutional filters throughout the network.VGG-16 has demonstrated success in various computer vision tasks.

2-ResNet-50 (Residual Network): ResNet-50 introduces the concept of residual learning, mitigating the vanishing gradient problem in deep networks. The architecture includes shortcut connections that enable the direct flow of information across layers. ResNet-50 has exhibited exceptional performance in image classification tasks. [4]

3-Inception V3: Inception V3 employs a unique architecture with multiple parallel paths for feature extraction. It incorporates 1x1, 3x3, and 5x5 convolutions. Inception V3 is recognized for the efficiency and has been successful in image recognition tasks. [5]

4-DenseNet-121 (Densely Connected Convolutional Networks): DenseNet-121 features dense connectivity, where each layer receives input from all previous layers. This architecture encourages feature reuse and facilitates gradient flow. DenseNet-121 has demonstrated effectiveness in various image analysis applications.
In the later sections of this paper, we delve into the methodology employed for training and evaluating these models, presenting results and insights gained from their application in the automated brain tumor identification. The comparative analysis of these models aims to discern their individual strengths and contributions in advancing image analysis for improved brain tumor diagnosis. This article, propose an efficient and effective method based on traditional products and neural networks to identify and segment brain tumors without human assistance. 

# PROPOSED WORK
A.	 MODEL 
In this project, there are multiple stages of research as can be seen from Fig. 1. In the form of research framework. In the proposed research framework: This is the basic structure of the CNN the model that we are going to use in our  project and compare the accuracies of various models and then conclude which model is the best. [9]

![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/814db51c-9cc0-4eab-bcf2-e4b5a49974dc)

Figure 1.Convolutional Neural Networks (CNNs)     

![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/0ff7b53c-aa96-4711-97d8-29f50266da15)

In figure no 2 we will propose the required flowchart that describe the entire working of the model and then we will  run all the models in our computer system and find accuracies and compare various models and find out which one deep learning model is the best.[10].

# Working
![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/5e905c5e-4fbc-4808-8922-e7537d185ad9)

 

Figure 2: Flowchart that explains working of proposed work
In clinical picture analysis, CNNs have emerged as a transformative technology, particularly noteworthy for their efficacy in tasks such as the automated detection of brain tumors.

# Import and Preprocessing

![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/15882482-e1d6-4a97-8607-9dbf9cb1ac10)

![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/f14c9ca2-1b78-4453-912c-0ec18e183606)

#Tumor No
![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/9aeb1a1a-acef-4414-b741-6a8b5254c9d7)

#Tumor Yes
![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/534067ca-f6b8-41b0-a25c-e95d8b07c684)

# CNN Model
Argumented Images
![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/5f3bee02-96b0-48d1-a13b-a5d4b773c275)

# CNN Model
![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/3f7c0ef9-9c4a-437f-a8af-9ae38ba8ca27)

# MODEL BUILDING -> Resnet50
![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/ce077e84-c243-4fb9-80be-c7c6506f915e)
# MODEL BUILDING - InceptionV3
![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/78f04f75-a043-4132-af00-ce465c47ee21)
# MODEL BUILDING - DenseNet121
![image](https://github.com/uniyalmanas/Brain-Tumor-detection-using-Deep-Learning/assets/77741645/a42dfbc1-8c86-4a60-961f-5561467eada1)


