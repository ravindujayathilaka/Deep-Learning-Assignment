# Deep-Learning-Assignment
Deep Learning Assignment 2023

Wanni Arachchige P.N -IT20617028

Herath H.M.U.R - IT20617400

Shalinda R.M.M - IT20607128

Jayathilaka S.A.D.R.P. - IT20631260


1.1	Problem

Agriculture is the backbone of our global food supply, and it faces numerous challenges in ensuring food security and sustainability. One of the most pressing challenges is the early detection and management of diseases affecting crop plants. Crop diseases can have catastrophic consequences, leading to reduced agricultural yields, economic losses for farmers, and even threats to food availability.
Traditionally, the identification of crop diseases has relied heavily on manual inspection by trained agronomists. However, this approach has limitations, including its subjectivity and the inability to detect diseases at their early stages when intervention is most effective. Moreover, as the global population continues to grow, the demand for food production increases, putting additional pressure on agriculture to produce more with limited resources.
In this context, the need for automated and accurate disease detection methods in agriculture becomes paramount. The ability to swiftly identify and classify diseases in crop leaves is essential for early intervention and targeted treatment, ultimately contributing to higher yields and food security.

1.2	Solution

Our project team has devised a comprehensive solution that leverages deep learning models for crop leaf disease detection. So, we focused on developing an automated system capable of accurately classifying and diagnosing diseases in the leaves of different crops, including,
•	Rice
•	Tea
•	Corn
•	Tomato
These models excel in distinguishing between healthy leaves and leaves affected by various diseases. By developing robust and accurate models that can classify diseases in crop leaves, we aim to provide farmers and agricultural stakeholders with a valuable tool for early diagnosis and effective disease management. 

1.3	Background Information – Algorithm Used

At the core of our solution are Convolutional Neural Networks (CNNs), a class of deep learning models well-suited for image classification tasks. CNNs have demonstrated remarkable accuracy in classifying diseases in crop leaves. As in the below figure, the CNN architecture we employ consists of multiple layers, including convolutional layers for feature extraction and pooling layers for downsampling. These layers, when appropriately configured, can capture both low-level and high-level features in the images, facilitating accurate disease classification.
 
The key components of our solution include advanced data preprocessing techniques, data augmentation, and the careful selection of CNN architectures tailored to each crop. These components collectively contribute to the accuracy and effectiveness of our disease detection models. 

1.4	Detailed Analysis of Chosen Dataset

Our research makes use of sizable datasets from Kaggle, which include a lot of pictures of both healthy and damaged plant leaves from different crop species. These datasets are invaluable resources, as they include images captured under controlled conditions, ensuring data quality and consistency.
Link for the dataset:- https://www.kaggle.com/datasets/mohitsingh1804/plantvillage 
In conjunction with these datasets, our project leverages the power of supervised learning, a fundamental approach in the field of machine learning. Supervised learning entails training a model on labeled data, where the model learns to make predictions based on input features while being guided by known target labels.
So, in our case, the labeled data consists of images of crop leaves, each associated with a specific label indicating whether the leaf is healthy or affected by a particular disease. During the training process, the model learns to recognize patterns and features in the images that are indicative of disease presence or absence.

