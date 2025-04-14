# Pneumonia Detection from Chest X-ray Images 🫁
📖 Project Overview
Pneumonia is a serious lung infection and a leading cause of death in children under five. This project focuses on detecting pneumonia from chest X-ray images using a deep learning model to assist in early and accurate diagnosis.

📂 Dataset
The dataset consists of chest X-ray images categorized into two classes:

PNEUMONIA

NORMAL

It was preprocessed and split into training, validation, and test sets. The test set includes 624 images.

🧠 Model
An EfficientNet-based CNN was trained for binary classification (NORMAL vs PNEUMONIA). The model was optimized for high recall on pneumonia cases to minimize false negatives.

📊 Results

Accuracy: 93%

Macro Avg F1-Score: 0.93

Weighted Avg F1-Score: 0.93

🚀 How to Run
1. Clone the repo
      git clone https://github.com/your-username/pneumonia-detection.git


📌 Notes
EfficientNet was chosen for its balance of accuracy and computational efficiency.

The model prioritizes minimizing false negatives to ensure critical pneumonia cases are caught.

📎 License
This project is open source under the MIT License.

