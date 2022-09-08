# Applied Data Science Capstone

## 📄 Summary
This capstone project will ultimately **predict if the Space X Falcon 9 first stage will land successfully**. 

The full report can be found [here](https://github.com/Ashwiin/IBM-Data-Science-Capstone-Project/blob/main/IBM%20Data%20Science%20Capstone%20Project%202022.pdf).

### Context and Business Understanding
- Space X promotes Falcon 9 rocket launch for a fee of 62 million dollars. At the same time, their competitors are charging more than 165 million dollars for each launch. The significant amount of savings coming from Space X is due to its ability to reuse the first stage.

- If we can predict whether the first stage will land, we can compute the cost of a launch and evaluate whether an alternative business should compete with SpaceX for a rocket launch.

## 📑 Main Topics 
This project follows these steps:
1. [Data Collection](https://github.com/Ashwiin/IBM-Data-Science-Capstone-Project/tree/main/01.%20Data%20Collection)
    - Making GET requests to the SpaceX REST API
    - Web Scraping
2. [Data Wrangling ](https://github.com/Ashwiin/IBM-Data-Science-Capstone-Project/tree/main/02.%20Data%20Wrangling)
    - Using the `.fillna()` method to remove NaN values
    - Using the `.value_counts()` method to determine the following:
        - Number of launches on each site
        - Number and occurrence of each orbit
        - Number and occurrence of mission outcome per orbit type
    - Creating a landing outcome label that shows the following:
        - 0 when the booster did not land successfully
        - 1 when the booster did land successfully
3. [Exploratory Data Analysis](https://github.com/Ashwiin/IBM-Data-Science-Capstone-Project/tree/main/03.%20Exploratory%20Data%20Analysis)
    - Using SQL queries to manipulate and evaluate the SpaceX dataset
    - Using Pandas and Matplotlib to visualize relationships between variables, and determine patterns
4. [Interactive Visual Analytics](https://github.com/Ashwiin/IBM-Data-Science-Capstone-Project/tree/main/04.%20Interactive%20Visual%20Analytics)
    - Geospatial analytics using Folium
    - Creating an interactive dashboard using Plotly Dash
5. [Predictive Analysis (Classification)](https://github.com/Ashwiin/IBM-Data-Science-Capstone-Project/tree/main/05.%20Predictive%20Analysis%20(Classification))
    - Using Scikit-Learn to:
        - Pre-process (standardize) the data
        - Split the data into training and testing data using train_test_split
        - Train different classification models
        - Find hyperparameters using GridSearchCV
    - Plotting confusion matrices for each classification model
    - Assessing the accuracy of each classification model

## 🔑 Key Skills Learned/Used 
- Using data science methodologies to define and formulate a real-world business problem
- Using data analysis and data visualisation to load a dataset, clean it, and find out interesting insights from it
- Interactive dashboard development with Plotly Dash
- Interactive map development using Folium
- Using machine learning to build a predictive model to help a business function more efficiently
- Structuring and building a data-findings report

## 🏆 Certificates 
To verify the certificates, click the images to follow the links.
