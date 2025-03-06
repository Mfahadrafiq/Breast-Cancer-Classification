# 🩺 Breast Cancer Classification using ANN  

## 📌 Overview  
This repository contains an **Artificial Neural Network (ANN)** model for classifying **breast cancer tumors** as **Malignant (M) or Benign (B)** using the **Wisconsin Breast Cancer Dataset**. The model is trained on **cellular features** extracted from biopsy images to provide an accurate diagnosis.  

## 📂 Project Structure  
```
|-- ANN Model.ipynb   # Jupyter Notebook containing the ANN model and training process
|-- data.csv          # Wisconsin Breast Cancer Dataset
|-- output/           # Contains model predictions and evaluation results
```

## 🚀 Installation  
Clone the repository and install dependencies:  
```sh
git clone https://github.com/mfahadrafiq/Breast Cancer Classification.git
cd Breast-Cancer-Classification
pip install -r requirements.txt
```

## 🛠️ Usage  
1. **Open the Jupyter Notebook**:  
   ```sh
   jupyter notebook "ANN Model.ipynb"
   ```
2. **Run the notebook** to:  
   - Load the dataset  
   - Preprocess the data  
   - Train the **ANN model**  
   - Evaluate the model performance  

## 🔍 Model Architecture  
- **Input Layer**: 30 features from biopsy images  
- **Hidden Layers**: Multiple Dense layers with ReLU activation  
- **Output Layer**: Sigmoid activation for binary classification  

### **Compilation & Training**  
- **Optimizer**: Adam  
- **Loss Function**: Binary Cross-Entropy  
- **Evaluation Metric**: Accuracy  

## 📊 Results  
The model was evaluated on the test dataset and achieved:  

| Metric  | Value  |
|---------|--------|
| **Accuracy** | **98.46%** |

## 📈 Visualization  
✔️ **Data distribution plots** (Seaborn)  
✔️ **Training Loss & Accuracy curves**  
