# Brain Tumour Detection Project
This project focuses on detecting brain tumors from MRI images using machine learning. The aim is to build a model that can accurately classify MRI scans as **Tumour** or **No Tumour**.
---
## Dataset
The dataset contains MRI images classified into two categories:

| Class        | Number of Images |
|--------------|------------------|
| Tumour       | 155              |
| No Tumour    | 98               |
| **Total**    | **253**          |

- **Image format:** JPEG/JPG
- **Image size:** Varies (e.g., 180x218 to 587x630 pixels)
- **Color mode:** Grayscale or RGB
- The dataset is organized into two folders: `yes` (tumour present) and `no` (tumour absent).
---
## Data Preprocessing
- Images are resized to a fixed dimension (e.g., 224x224 pixels) before feeding into the model.
- Data augmentation techniques (rotation, flipping, zoom) are applied to increase data variability and reduce overfitting.
- Dataset is split into training and testing sets with an 80-20 ratio.
---
## Machine Learning Model
- A Convolutional Neural Network (CNN) is used for classification.
- The model architecture can be custom or based on popular pre-trained networks such as VGG16 or ResNet.
- The model is trained on the preprocessed dataset to learn distinguishing features.
---
## Evaluation Metrics
| Metric     | Description                                   | Score (Example) |
|------------|-----------------------------------------------|-----------------|
| Accuracy   | Overall correctness of predictions             | 89%             |
| Precision  | Correctly predicted tumors out of all predicted tumors | 85%     |

