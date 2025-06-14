# SVM Classification and Visualization  

This project demonstrates building and visualizing a Support Vector Machine (SVM) model's classification performance and decision boundary using a spam classification dataset.

## Dataset  
The dataset used is `spam_classification_dataset.csv` and includes the following features:
- **Email_Length**: Length of the email in characters.  
- **Hyperlinks**: Number of hyperlinks in the email.  
- **Keyword_Frequency**: Frequency of specific keywords in the email.  
- **Special_Characters**: Count of special characters used.  
- **Is_Spam**: Target variable indicating if the email is spam (1) or not (0).  

## Steps Performed  
1. **Data Visualization**: Used `seaborn` to analyze feature relationships with the target variable (`Is_Spam`).  
2. **Data Preprocessing**: 
   - Split the dataset into features (`X`) and target (`y`).  
   - Divided data into training and testing sets using `train_test_split`.  
   - Scaled features using `StandardScaler` for better performance with SVM.  
3. **Model Training**:  
   - Trained an SVM model with a linear kernel on the scaled training data.  
   - Evaluated the model's accuracy on the test data using `accuracy_score`.  
4. **Visualization of Decision Boundary**:  
   - Selected the first two features for 2D visualization.  
   - Trained another SVM model and plotted the decision boundary using `matplotlib`.  

