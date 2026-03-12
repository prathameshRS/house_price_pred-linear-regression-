🏠 House Price Prediction using Linear Regression
A beginner Machine Learning project that predicts house prices in California using Linear Regression.

📌 What This Project Does
This project teaches a computer to predict the price of a house by looking at details like:

Income of people in the area
Age of the house
Number of rooms
Location (Latitude & Longitude)


📊 Dataset

Name: California Housing Dataset
Source: Built inside Scikit-learn library
Size: 20,640 houses
Features: 8 input features + 1 target (price)

ColumnMeaningMedIncMedian income of people in areaHouseAgeHow old the house isAveRoomsAverage number of roomsAveBedrmsAverage number of bedroomsPopulationHow many people live in areaAveOccupAverage people per houseLatitudeLocation (north/south)LongitudeLocation (east/west)PriceHouse price in $100,000s ← what we predict

🛠️ Tools Used
ToolPurposePythonProgramming languageNumPyFor numbers and mathPandasFor tables and dataMatplotlibFor drawing graphsScikit-learnFor ML algorithmsJupyter NotebookFor writing and running code

🚀 How to Run This Project
Step 1 — Install Anaconda
Download from: https://www.anaconda.com/download
Step 2 — Open Jupyter Notebook
Search Anaconda Navigator → Click Launch under Jupyter Notebook
Step 3 — Install Libraries
Open a new cell and type:
bashpip install scikit-learn pandas numpy matplotlib
Step 4 — Run the Notebook
Open linear_regression.ipynb and run each cell one by one using Shift + Enter

📝 Steps I Followed
Step 1 → Imported all libraries
Step 2 → Loaded the California Housing dataset
Step 3 → Explored the data (shape, columns, stats)
Step 4 → Checked for missing values
Step 5 → Drew graphs to see patterns
Step 6 → Prepared X (inputs) and y (price)
Step 7 → Split data → 80% train, 20% test
Step 8 → Trained the Linear Regression model
Step 9 → Checked R² score
Step 10 → Predicted a brand new house price!

📈 Results
MetricScoreR² Score0.57MeaningModel understood 57% of house price pattern

📉 What is R² Score?
R² Score tells us how good our model is:
1.0 → Perfect model
0.9 → Excellent
0.7 → Good
0.57 → Decent (our score)
0.0 → Useless model

💡 What I Learned

What Linear Regression is and how it works
How to load and explore a real dataset
What X (inputs) and y (target) mean
Why we split data into train and test
How to train a model using model.fit()
How to make predictions using model.predict()
How to evaluate a model using R² score


🔮 Sample Prediction
pythonnew_house = {
    'MedInc'    : 5.0,    # income in area
    'HouseAge'  : 10,     # house is 10 years old
    'AveRooms'  : 6.0,    # 6 rooms
    'AveBedrms' : 1.0,    # 1 bedroom
    'Population': 1000,   # 1000 people in area
    'AveOccup'  : 3.0,    # 3 people per house
    'Latitude'  : 34.0,   # Los Angeles area
    'Longitude' : -118.0
}

Predicted Price → $238,000

Follow Me On Medium :https://medium.com/@prathameshsahastrabuddhe2003
