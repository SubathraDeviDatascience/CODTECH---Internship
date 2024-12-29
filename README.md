# Overview of the Project

## **Project Title** : Linear Regression on Housing Prices

### Objective
It demonstrates the use of linear regression to predict housing prices based on various features such as square footage, number of bedrooms, number of bathrooms, and location.
By using a simple dataset, we explore how these variables influence housing prices and visualize the relationship between them.

### Dataset
The dataset consists of the following columns:

 - **SquareFootage** : The size of the house in square feet.

 - **Bedrooms** : The number of bedrooms in the house.

 - **Bathrooms** : The number of bathrooms in the house.

 - **Location** : Whether the house is located inside or outside the city.

 - **Price** : The price of the house in dollars.

### Key Activities

**1. Data Preparation**

    - Convert the data into a pandas DataFrame.
    - Encode the categorical 'Location' column using LabelEncoder.

**2. Feature Selection**

    - Select features (SquareFootage, Bedrooms, Bathrooms, Location) and target variable (Price).

**3. Model Training**

    - Use LinearRegression from the scikit-learn library to train the model on the dataset.

**4. Prediction**

    - Predict housing prices using the trained model.
    - Visualize the actual vs. predicted prices using matplotlib.

### Output
![image](https://github.com/user-attachments/assets/48443884-38c5-4477-8fbf-e4ee77cb6af1)

### Conclusion
This project provides a clear example of applying linear regression to real-world data to predict housing prices. 
By understanding the influence of various features on housing prices, we can make more informed decisions in real estate markets.
