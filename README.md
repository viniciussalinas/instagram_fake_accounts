## Instagram Fake Accounts Classification

This Jupyter Notebook, "instagram-fake-accounts.ipynb," focuses on the development of a classification model to identify fake Instagram accounts. The model assesses various attributes of Instagram profiles and classifies them as either fake or genuine.

### Problem Statement
The proliferation of fake accounts on Instagram has become a major concern. These accounts can be used for various fraudulent activities, including spreading misinformation or engaging in spam. Detecting and flagging such accounts is crucial for maintaining the platform's integrity.

### Data Source
The dataset used for this project can be accessed via the following link: [Instagram Fake, Spammer, Genuine Accounts Dataset.](https://www.kaggle.com/datasets/free4ever1/instagram-fake-spammer-genuine-accounts)

### Key Steps
- Load and merge dataset files: The data is collected from multiple files and combined to create a unified dataset.
- Data Exploration: The combined dataset is explored to understand its structure and contents.
- Data Preparation: The dataset is divided into predictor variables and the target variable.
- Train-Test Split: A split is performed to allocate 80% of the data for training and 20% for testing.
- Model Development: An Extra Trees Classifier model is created to predict fake Instagram accounts.
- Model Evaluation: The model's accuracy is evaluated and analyzed for performance.
- Conclusion: The project concludes with insights on the model's applicability and potential for further improvement.

### Model Performance
The model exhibits a high accuracy of over 90% when tested with a dataset containing 696 records. With additional data for training and testing, the model's accuracy is expected to further increase. This solution can play a crucial role in identifying fake Instagram accounts, thereby addressing the problem outlined in the report.

For a detailed examination of the code and results, please refer to the "instagram-fake-accounts.ipynb" Jupyter Notebook.
