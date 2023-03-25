# K-Nearest-Neighbors-Project
This project is a classification problem that aims to build a K Nearest Neighbors (KNN) model to classify the target class given the features of the dataset.

### Table of Contents
- Getting Started
- Prerequisites
- Installing
- Project Structure
- Dataset
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Training and Evaluation
- Choosing K Value
- Conclusion

### Getting Started
To get started with the project, you need to clone the repository by running the following command in your terminal:

```
git clone https://github.com/<your-username>/<your-repo-name>.git
```
This will create a copy of the project on your local machine that you can work on.

### Prerequisites
The project requires the following libraries to be installed:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

You can install these libraries using pip by running the following command:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Installing
There is no installation required for this project, as it is a standalone Jupyter Notebook file.

### Project Structure
The project contains the following files:

- `KNN_Project.ipynb`: Jupyter Notebook file that contains the code for the project.
- `KNN_Project_Data.csv`: CSV file that contains the dataset used in the project.

### Dataset
The dataset used in this project is an artificial dataset with 1,000 observations and 11 features. The target class is a binary variable that takes on the values of 0 and 1.

### Exploratory Data Analysis (EDA)
The EDA section uses the Seaborn library to create a pairplot of the dataset, with the hue indicated by the target class column. This helps to visualize the relationship between the different features and the target class.

### Data Preprocessing
The data preprocessing section involves standardizing the variables using the StandardScaler object from Scikit-learn. The scaled features are then transformed into a DataFrame and split into a training and testing set using the train_test_split method from Scikit-learn.

### Model Training and Evaluation
The KNN model is trained using the KNeighborsClassifier object from Scikit-learn, with n_neighbors set to 1. The model is evaluated using the confusion matrix and classification report from Scikit-learn.

### Choosing K Value
The K value for the KNN model is chosen using the elbow method. A for loop is used to train various KNN models with different K values, and the error rate for each of these models is tracked in a list. The error rate is then plotted against the K value, and the optimal K value is chosen based on the elbow point in the graph.

### Conclusion
In conclusion, the K Nearest Neighbors algorithm is a simple yet effective machine learning algorithm that can be used for classification problems. The project demonstrated how to implement the KNN algorithm in Python using Scikit-learn and how to choose the optimal K value using the elbow method.



