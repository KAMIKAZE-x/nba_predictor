### 🔍 **Project Summary**

In this end-to-end project, we’ll build a machine learning model to predict NBA game winners. The process starts with scraping NBA box score data from the web, followed by cleaning and parsing it using **BeautifulSoup** and **pandas**. Once the data is structured, we’ll perform **feature selection**, train a predictive model, and then enhance it further using **rolling features** for better accuracy.

This project combines **web scraping, data preprocessing, and machine learning** into a complete workflow.

---

### ✅ **Project Workflow**

1. Scrape NBA standings and box scores.
2. Clean and structure HTML data using BeautifulSoup.
3. Convert box scores into a pandas DataFrame.
4. Identify important features through feature selection.
5. Train a machine learning model for predictions.
6. Use rolling statistics to improve the model's performance.

---

### 📁 **Project Files**

- `get_data.ipynb` – Scrapes NBA box scores from Basketball Reference.  
- `parse_data.ipynb` – Cleans and organizes the scraped data into a structured DataFrame.  
- `predict.ipynb` – Trains and evaluates a machine learning model to predict game outcomes.

---

### 📚 **What You Should Know Before Starting**

To work on this project, you should be comfortable with:

- Python basics: functions, conditionals, loops, and data structures
- Cleaning and manipulating data using pandas
- Working in Jupyter notebooks
- Fundamentals of machine learning

It’s recommended to complete these **Dataquest courses** (or know equivalent concepts):

- Python Basics
- For Loops & If Statements
- Dictionaries & Functions
- Intermediate Python
- Pandas & NumPy
- Data Cleaning
- Machine Learning Foundations

---

### 🛠 **Local Setup**

#### 🔧 Installation Requirements:

- **Python 3.8+**
- **JupyterLab**

#### 📦 Required Python Packages:

- `pandas`
- `scikit-learn`
- `beautifulsoup4`
- `playwright`

---

### 📊 **Data Source**

All game data will be scraped from **Basketball Reference**.

If you'd prefer not to scrape the data yourself, you can use these:

- **Pre-scraped data files** (provided in the project repo)
- **Box score CSV** for the prediction part, if you only want to work on the machine learning stage
