This project aims to predict Parkinson’s disease using machine learning algorithms, ensuring high accuracy and reliability. The dataset used contains biomedical voice measurements from patients, with features extracted to detect early signs of Parkinson’s. The project employs three different machine learning models: Support Vector Machine (SVM), Random Forest, and Logistic Regression.

The dataset is preprocessed by removing irrelevant columns and standardizing features using StandardScaler. The data is split into training and testing sets to evaluate model performance. Each model is trained separately, and their accuracy is measured. To enhance reliability, majority voting is implemented—if at least two models predict a positive result, the final output is "Positive, Parkinson’s Found"; otherwise, "Negative, No Parkinson’s Found."

The project provides a single input prompt for patient data, allowing users to enter biomedical voice metrics. The system then processes this input and generates predictions based on all three models. This multi-model approach ensures robustness and reduces errors caused by a single algorithm’s limitations.

This project is valuable for early detection of Parkinson’s disease, aiding medical professionals in making informed decisions. It highlights the potential of AI in healthcare, providing a non-invasive, efficient diagnostic tool. 
