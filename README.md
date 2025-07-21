# Breast-Cancer-ML-Model-Naive-Bayes-Approach

## Objective
The aim of this project is to build a predictive machine learning model using the Breast Cancer Wisconsin (Diagnostic) dataset to classify tumors as malignant or benign. The Naive Bayes algorithm was used to evaluate the potential of statistical classification in medical screening.
## Skills Gained
- Supervised machine learning using classification models
- Model evaluation through accuracy, confusion matrix, and classification report
- Data preprocessing and visualization
- Application of Naive Bayes algorithm
- Feature analysis and dataset interpretation using pandas and matplotlib
## Tools Utilized (Python Libraries)
- pandas
- scikit-learn
- numpy
- matplotlib
- seaborn
## Procedures
1. **Load Dataset**  
   Loaded the built-in Breast Cancer dataset from sklearn.datasets.

2. **Explore and Understand the Data**  
   Inspected dataset shape, feature names, class distribution, and sample records.

3. **Preprocess the Data**  
   - Split the dataset into features (X) and labels (y) 
   - Split into training and testing sets using an 80:20 ratio

4. **Build Model**  
   - Used GaussianNB from sklearn.naive_bayes to create a Naive Bayes classifier 
   - Trained the model using the training dataset.

5. **Model Prediction and Evaluation**  
   - Predicted labels using the test dataset.
   - Evaluated performance with accuracy score, confusion matrix, and classification report.

6. **Analysis of the Results**  
   - Predicted and actual values were compared against each other.
   - Interpreted false positives and false negatives.
   - Assessed class-wise precision, recall, and F1-score

## Conclusion  
The Naive Bayes model achieved an accuracy of approximately 97.4 percent on the test set. It correctly identified all benign tumors and misclassified only 3   malignant ones. The precision for detecting malignant tumors was 100 percent, while the recall for benign tumors was slightly lower at 93 percent. These results suggest that the model performs reliably in distinguishing between malignant and benign tumors, with minimal false negatives, making it a strong candidate for supporting early detection efforts in medical screening settings.
