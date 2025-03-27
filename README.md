# Network Intrusion Detection System (NIDS) - Cybersecurity Threat Classification Using Machine Learning

## **How to Run the Code**

### **Step 1: Clone the Repository**
Clone this project to your local machine or download the ZIP file.
```bash
git clone <repository-link>
cd <project-folder>
```

### **Step 2: Install Dependencies**
Make sure you have Python installed. Install the required packages using the following command:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### **Step 3: Dataset Preparation**
- Place the training and testing dataset files (`Train_data.csv` and `Test_data.csv`) in the same directory as the script.
- Update the dataset paths in the code if necessary:
```python
train_path = 'D:/nids/Train_data.csv'
test_path = 'D:/nids/Test_data.csv'
```

### **Step 4: Run the Code**
Run the Python script to execute the project:
```bash
python <script-name>.py
```

### **Step 5: View the Results**
- The classification reports and accuracy scores for Random Forest and SVM models will be displayed.
- Confusion Matrix visualization will appear, showing the classification results.

---

### **Note:**
- Ensure you have proper permissions to read the dataset files.
- Adjust dataset paths in the code if running in a different environment.



