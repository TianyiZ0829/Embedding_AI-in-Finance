# Embedding_AI-in-Finance

### **Author**: Tianyi Zhu  

## **Project Overview**
This project focuses on fine-tuning the BERT model for text classification tasks, specifically using **business descriptions** as input data. The implementation includes data preprocessing, tokenization, dataset splitting, and fine-tuning BERT for classification.

---

## **Table of Contents**
1. [Project Workflow](#project-workflow)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Results](#results)
7. [License](#license)

---

## **Project Workflow**

### **Step 1**: Data Preprocessing
- Clean and process the input data (business descriptions).
- Tokenize text using Hugging Face Transformers library.

### **Step 2**: Dataset Splitting
- Split the dataset into training, validation, and test sets for model evaluation.

### **Step 3**: Fine-Tuning BERT
- Load the pretrained BERT model.
- Fine-tune the model for sequence classification tasks using PyTorch and Hugging Face.

### **Step 4**: Evaluation and Results
- Evaluate the fine-tuned model on test data.
- Visualize the results using **matplotlib** and **seaborn**.

---

## **Requirements**

Ensure you have the following Python libraries installed:
- `transformers`
- `torch`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `tqdm`

---

## **Installation**

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/AS12-BERT-Classification.git
   cd AS12-BERT-Classification
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**

1. **Run the notebook**:  
   Open the Jupyter Notebook `AS12.ipynb` in a Jupyter environment:
   ```bash
   jupyter notebook AS12.ipynb
   ```

2. **Steps in the Notebook**:
   - Data preprocessing
   - Tokenization
   - Fine-tuning BERT
   - Model evaluation and results

3. **Input Data**: Ensure you have the business description data in the correct format.

---

## **File Structure**

```
AS12-BERT-Classification/
│-- AS12.ipynb              # Main Jupyter Notebook for implementation
│-- data/                   # Folder to store input data
│-- results/                # Folder to save outputs and visualizations
│-- models/                 # Folder to save fine-tuned models
│-- README.md               # Project documentation
│-- requirements.txt        # Required dependencies
```

---

## **Results**

- Results of fine-tuning the BERT model, including evaluation metrics, are documented in the notebook.
- Visualizations include confusion matrices and classification accuracy plots.

---

