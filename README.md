# 🏠 House Price Prediction using Linear Regression

A beginner-friendly Machine Learning project that predicts house prices in California using Linear Regression.

---

## 📌 What This Project Does

This project teaches a computer to predict the price of a house by analyzing key features such as:

- 💰 **Income** of people in the area
- 📅 **Age** of the house
- 🛏️ **Number of rooms**
- 📍 **Location** (Latitude & Longitude)

---

## 📊 Dataset

| Property | Details |
|----------|---------|
| **Name** | California Housing Dataset |
| **Source** | Built inside Scikit-learn library |
| **Size** | 20,640 houses |
| **Features** | 8 input features + 1 target (price) |

### Dataset Columns

| Column | Meaning |
|--------|---------|
| `MedInc` | Median income of people in area |
| `HouseAge` | How old the house is |
| `AveRooms` | Average number of rooms |
| `AveBedrms` | Average number of bedrooms |
| `Population` | How many people live in area |
| `AveOccup` | Average occupancy per house |
| `Latitude` | Latitude coordinate |
| `Longitude` | Longitude coordinate |
| `MedHouseVal` | Median house value (target) |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Python** | Programming language |
| **NumPy** | For numbers and math |
| **Pandas** | For tables and data |
| **Matplotlib** | For drawing graphs |
| **Scikit-learn** | For ML algorithms |
| **Jupyter Notebook** | For writing and running code |

---

## 🚀 How to Run This Project

### Step 1 — Install Anaconda
Download from: https://www.anaconda.com/download

### Step 2 — Open Jupyter Notebook
Search for **Anaconda Navigator** → Click **Launch** under **Jupyter Notebook**

### Step 3 — Install Libraries
Open a new cell and type:
```bash
pip install scikit-learn pandas numpy matplotlib
```

### Step 4 — Run the Notebook
Open `linear_regression.ipynb` and run each cell one by one using **Shift + Enter**

---

## 📝 Steps I Followed

1. ✅ Imported all libraries
2. ✅ Loaded the California Housing dataset
3. ✅ Explored the data (shape, columns, stats)
4. ✅ Checked for missing values
5. ✅ Drew graphs to see patterns
6. ✅ Prepared X (inputs) and y (price)
7. ✅ Split data → 80% train, 20% test
8. ✅ Trained the Linear Regression model
9. ✅ Checked R² score
10. ✅ Predicted a brand new house price!

---

## 📈 Results

| Metric | Score |
|--------|-------|
| **R² Score** | 0.57 |

**What does this mean?** The model understood 57% of the house price pattern.

---

## 📉 Understanding R² Score

R² Score tells us how good our model is:

- ✅ **1.0** → Perfect model
- ✅ **0.9** → Excellent
- ✅ **0.7** → Good
- ✅ **0.57** → Decent (our score)
- ❌ **0.0** → Useless model

---

## 💡 What I Learned

- ✅ What Linear Regression is and how it works
- ✅ How to load and explore a real dataset
- ✅ What X (inputs) and y (target) mean
- ✅ Why we split data into train and test
- ✅ How to train a model using `model.fit()`
- ✅ How to make predictions using `model.predict()`
- ✅ How to evaluate a model using R² score

---

## 🔮 Sample Prediction

```python
new_house = {
    'MedInc'     : 5.0,      # income in area
    'HouseAge'   : 10,       # house is 10 years old
    'AveRooms'   : 6.0,      # 6 rooms
    'AveBedrms'  : 1.0,      # 1 bedroom
    'Population' : 1000,     # 1000 people in area
    'AveOccup'   : 3.0,      # 3 people per house
    'Latitude'   : 34.0,     # Los Angeles area
    'Longitude'  : -118.0    # Los Angeles area
}

# Predicted Price → $238,000
```

---

## 📚 Resources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)

---

## 👨‍💻 Author

Follow me on **[Medium](https://medium.com/@prathameshsahastrabuddhe2003)**

---

**Happy Learning!** 🚀