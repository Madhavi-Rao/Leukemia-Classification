
# Leukemia Classification
Leukemia is cancer of the body's blood-forming tissues, including the bone marrow and the lymphatic system. The bone marrow produces an excessive amount of abnormal white blood cells. These abnormal cells can crowd out healthy blood cells in the bone marrow

### Types of Leukemia
#### 1) How fast leukemia progresses:

* Acute leukemia (more serious sysmptoms)
* Chronic leukemia

#### 2) Type of White blood cells
* Lymphocytic leukemia
* Myelogenous leukemia

##### Acute lymphocytic leukemia (ALL)
##### Acute myelogenous leukemia (AML)
##### Chronic lymphocytic leukemia (CLL).
##### Chronic myelogenous leukemia (CML).

## Project Overview
* This project aimed to create a deep learning architecture that can address the classification issue in cancer cell imaging. 
* It was motivated by the ISBI 2019 C-NMC Challenge dataset.
    [Dataset](https://www.kaggle.com/datasets/andrewmvd/leukemia-classification/data)
* Using pre-trained neural networks to classify malignant lymphoblastic cells.

* The networks VGG16, ResNet50, VGG19 and EfficientNet each tried fitting the model to the problem with both feature extraction and fine-tuning.

* Next, average ensemble approach was implemented that might combine the best networks, VGG16 and Xception.

* The model's performance was compared with mentioned pre-trained models based on precision, recall, accuracy, and F1 score.

## Proposed Approach

![PA](https://github.com/user-attachments/assets/5e7e13b8-3c3f-44f2-b812-99c85422f683)

## Result
EfficientNet achieved high F1-score of  95.72% and accuracy  of 94%



![TT](https://github.com/user-attachments/assets/31b178ac-c89b-4747-8da6-cf392940b52b)




 
















