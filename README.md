# QR Code Authentication: Detecting Original vs. Counterfeit Prints

## 📌 Project Overview
This project aims to develop a **machine learning-based authentication system** to distinguish between original QR codes (**first prints**) and counterfeit copies (**second prints**). The approach involves **feature extraction, traditional machine learning models, and deep learning techniques** to detect subtle differences in print quality and microscopic patterns.

## 🚀 Features
- **Data Exploration & Analysis** – Identify key differences between original and counterfeit QR codes.
- **Feature Engineering** – Extract features using **OpenCV**, edge detection, and texture analysis.
- **Machine Learning Models** – Implemented **SVM, Random Forest, and CNN-based deep learning** approaches.
- **Performance Evaluation** – Compare models using **accuracy, precision, recall, F1-score, and confusion matrices**.
- **Deployment Considerations** – Discuss real-world implementation challenges and solutions.

## 📂 Project Structure
```
📁 QR-Code-Authentication
│-- 📂 data/                # Dataset (Original & Counterfeit QR codes)
│-- 📂 models/              # Saved trained models
│-- 📂 notebooks/           # Jupyter notebooks for EDA & modeling
│-- 📂 reports/             # Project report and documentation
│-- 📜 requirements.txt     # Python dependencies
│-- 📜 README.md            # Project description
│-- 📜 main.ipynb           # Main Jupyter Notebook
```

## 🔬 Methodology
1. **Data Exploration & Preprocessing**
   - Visualizing differences in **edge sharpness, texture patterns, and entropy**.
   - Normalization and augmentation techniques for better generalization.

2. **Feature Extraction**
   - **Edge Detection** (Canny algorithm) to highlight print quality differences.
   - **Texture Analysis** using Local Binary Pattern (**LBP**) histograms.
   - **Statistical Measures** (Mean, Variance, Entropy) for distinguishing patterns.

3. **Model Development**
   - **Traditional ML:** Support Vector Machine (**SVM**) & Random Forest (**RF**).
   - **Deep Learning:** Convolutional Neural Network (**CNN**) for automated feature extraction.

4. **Performance Evaluation**
   - Metrics: **Accuracy, Precision, Recall, F1-Score, Confusion Matrix**.
   - Comparison of ML and Deep Learning approaches.

## 📊 Results
| Model        | Accuracy | Precision | Recall | F1-Score |
|-------------|----------|-----------|--------|----------|
| SVM         | 97.5%    | 98%       | 97%    | 98%      |
| Random Forest | 92.5%  | 94%       | 93%    | 92%      |
| CNN         | TBD%     | TBD%      | TBD%   | TBD%     |

_SVM outperformed Random Forest in accuracy and recall, making it the preferred model._

## ⚡ Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/QR-Code-Authentication.git
cd QR-Code-Authentication
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run Jupyter Notebook
```bash
jupyter notebook
```

## 🛠️ Future Enhancements
- Improve **deep learning performance** with data augmentation.
- Increase robustness against **varying lighting and scanning conditions**.
- Deploy as a **real-time QR code authentication API**.

## 📝 License
This project is open-source and available under the **MIT License**.

---
💡 _Developed by [Your Name] – Passionate about AI, Security, and Computer Vision!_ 🚀
