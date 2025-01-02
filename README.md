# **Multi-Task and Multi-Modal Learning for Early Detection of Alzheimer’s Disease**

## **Overview**
This repository contains the resources, code, and datasets used for the research article *"Multi-Task and Multi-Modal Learning for Early Detection of Alzheimer’s Disease Using Transfer Learning."* The study explores an innovative approach to Alzheimer’s Disease (AD) detection by integrating features from MRI imaging and speech data using state-of-the-art machine learning techniques.

---

## **Key Features**
- **Multi-modal Learning**: Combines MRI and speech data to improve diagnostic accuracy.  
- **Transfer Learning**: Utilizes ResNet50 for MRI feature extraction.  
- **Speech Feature Analysis**: Extracts handcrafted features such as MFCCs, jitter, shimmer, and HNR.  
- **Fusion Model**: Integrates MRI and speech features using an attention-based fusion mechanism.  
- **Robust Evaluation**: Includes accuracy, precision, recall, F1-score, and confusion matrices.  

---

## **Usage Instructions**

### **1. Clone the Repository**
```bash
git clone https://github.com/username/alzheimer-detection.git
cd alzheimer-detection
2. Install Dependencies
bash
Copy code
pip install -r requirements.txt
3. Run Notebooks
Navigate to the notebooks/ folder and run the Jupyter notebooks:
mri_classification.ipynb for MRI-based classification.
speech_feature_extraction.ipynb for speech data processing.
fusion_model_training.ipynb for training the fusion model.
Datasets
MRI Data: Augmented Alzheimer MRI Dataset V2
Speech Data: ADReS Challenge dataset (details provided in the article).
Audio Files
Please note that due to GitHub's file size limit of 100 MB, the audio files could not be uploaded directly to this repository. Instead, you can access the audio files here.

Key Results
MRI Model Accuracy: 97.1%
Speech Model Accuracy: 63.5%
Fusion Model Accuracy: 89.4%
Contributors
Meryam Eddaif
D. Es-Souissy
Dr. S. Hamida
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
We thank Dr. S. Hamida for his supervision and guidance throughout this research.

Thank you for exploring this repository! Feel free to reach out for any questions or collaborations.
