# DermAI: 3D Total Body Photography for Early Skin Cancer Detection

## Project Description
DermAI is a cutting-edge machine learning project developed for the 'ISIC 2024 - Skin Cancer Detection with 3D-TBP' Kaggle competition. It focuses on differentiating malignant from benign skin lesions using binary classification algorithms on 3D total body photography images. This technology aims to improve triage and early detection of skin cancer in settings lacking specialized dermatologic care. Utilizing advanced machine learning techniques, this project processes and analyzes high-resolution 3D images to provide critical insights into skin health, potentially saving lives through early intervention.

## Technical Description
The project leverages Python and LightGBM, along with libraries such as NumPy, Pandas, and Matplotlib, to handle data processing and visualization. Advanced feature engineering techniques—such as lesion size ratios, color and texture analysis, and spatial geometry features—are employed to enhance model accuracy. These features help in capturing intricate details and variations in skin lesions that are critical for accurate classification.

## Results
Our model achieves robust performance metrics, with a focus on high clinical relevance:
- **Partial Area Under the ROC Curve (pAUC)**: Specifically tailored to capture model performance above the 80% true positive rate, crucial for medical diagnostic accuracy.
- **Top-15 Retrieval Sensitivity**: This metric highlights the model's capability to identify the most critical cases that require immediate attention by a dermatologist.

## Installation and Usage
To set up and run this project on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/blazingphoenix7/Early-Skin-Cancer-Detection-AI.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Early-Skin-Cancer-Detection-AI
   ```

3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Download the dataset:**
   Dataset link - [IISC Dataset](https://www.kaggle.com/competitions/isic-2024-challenge/data). 
   Extract the zip files to the local location where you cloned this repo

5. **Run the Early-Skin-Cancer-Detection-lgbm.ipynb file:**
   Make sure to change the paths in the ipynb file to the location where you have saved the ISIC 2024 dataset.

## Contributing
We welcome contributions to improve the algorithm's efficiency or test it with different datasets. Please feel free to fork the repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is made available under the MIT License. See the LICENSE file for more details.

## Acknowledgments
Kaggle and the ISIC for organizing the competition and providing the dataset.
All the researchers and developers whose libraries facilitated this project.
Mentors and collaborators who provided insights and reviews throughout the development process.
