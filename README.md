# SpaceX Falcon 9 First Stage Landing Prediction

## IBM Data Science Professional Certificate - Capstone Project

This project is the capstone for the IBM Data Science Professional Certificate program on Coursera. The goal is to predict whether SpaceX Falcon 9 first stage rockets will land successfully, which directly impacts launch costs and competitive pricing in the commercial space industry.

## 🚀 Project Overview

SpaceX advertises Falcon 9 rocket launches at $62 million, significantly lower than competitors who charge upwards of $165 million. This cost advantage stems from SpaceX's ability to reuse the first stage of their rockets. By predicting first stage landing success, we can estimate launch costs and provide valuable insights for companies bidding against SpaceX.

## 📊 Project Components

### 1. Data Collection
- **API Data Collection** (`jupyter-labs-spacex-data-collection-api.ipynb`)
  - Collect launch data from SpaceX REST API
  - Extract rocket information, payload details, launch sites, and landing outcomes
  - Parse and structure data for analysis

- **Web Scraping** (`jupyter-labs-webscraping.ipynb`)
  - Scrape Falcon 9 and Falcon Heavy launch records from Wikipedia
  - Supplement API data with additional historical information

### 2. Data Wrangling & Feature Engineering
- **Data Wrangling** (`labs-jupyter-spacex-Data wrangling.ipynb`)
  - Clean and preprocess collected data
  - Handle missing values and data inconsistencies
  - Create meaningful features for machine learning

### 3. Exploratory Data Analysis (EDA)
- **EDA with Visualization** (`EDA with Visualization Lab.ipynb`)
  - Analyze launch success rates by various factors
  - Visualize trends in SpaceX launch history
  - Identify patterns in landing success

- **SQL Analysis** (`jupyter-labs-eda-sql-coursera_sqllite.ipynb`)
  - Perform database queries to extract insights
  - Analyze launch data using SQL operations

### 4. Interactive Visual Analytics
- **Folium Maps** (`lab_jupyter_launch_site_location.ipynb`)
  - Interactive maps showing launch sites
  - Geographic analysis of launch locations
  - Proximity analysis to key infrastructure

- **Plotly Dashboard** (`spacex_dash_app.py`)
  - Interactive dashboard for exploring launch data
  - Real-time filtering by launch site and payload mass
  - Success rate visualizations

### 5. Machine Learning Prediction
- **Predictive Modeling** (`SpaceX_Machine Learning Prediction.ipynb`)
  - Train multiple classification algorithms
  - Compare model performance (Logistic Regression, SVM, Decision Tree, KNN)
  - Hyperparameter tuning with GridSearchCV
  - Model evaluation and selection

## 🛠️ Technologies Used

- **Python Libraries:**
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `requests` - API data collection
  - `beautifulsoup4` - Web scraping
  - `matplotlib` & `seaborn` - Data visualization
  - `plotly` - Interactive visualizations
  - `folium` - Interactive maps
  - `scikit-learn` - Machine learning algorithms
  - `dash` - Web application framework

- **Development Environment:**
  - Jupyter Notebooks
  - Python 3.x

## 📁 File Structure

```
Space-X-DS-Project/
├── README.md
├── jupyter-labs-spacex-data-collection-api.ipynb    # API data collection
├── jupyter-labs-webscraping.ipynb                   # Web scraping
├── labs-jupyter-spacex-Data wrangling.ipynb         # Data preprocessing
├── EDA with Visualization Lab.ipynb                 # Exploratory analysis
├── jupyter-labs-eda-sql-coursera_sqllite.ipynb      # SQL analysis
├── lab_jupyter_launch_site_location.ipynb           # Geographic analysis
├── SpaceX_Machine Learning Prediction.ipynb         # ML modeling
├── spacex_dash_app.py                               # Interactive dashboard
└── spacex_launch_dash.csv                           # Dashboard data
```

## 🎯 Key Findings

- Successfully built predictive models achieving ~85% accuracy
- Identified key factors influencing landing success:
  - Launch site location
  - Payload mass
  - Rocket version and reusability
  - Flight number progression
- Decision Tree and SVM models performed best for this classification task

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn plotly dash folium scikit-learn beautifulsoup4 requests
```

### Running the Project

1. **Data Collection:** Start with the API collection and web scraping notebooks
2. **Data Processing:** Run the data wrangling notebook
3. **Analysis:** Execute EDA notebooks for insights
4. **Modeling:** Run the machine learning prediction notebook
5. **Dashboard:** Launch the interactive dashboard:
   ```bash
   python spacex_dash_app.py
   ```

## 📈 Results & Impact

This project demonstrates the complete data science workflow:
- **Data Engineering:** Collected and processed real-world data from multiple sources
- **Statistical Analysis:** Discovered meaningful patterns in SpaceX launch data
- **Machine Learning:** Built predictive models with practical business applications
- **Data Visualization:** Created compelling visual narratives
- **Business Intelligence:** Provided actionable insights for competitive analysis

## 🏆 Skills Demonstrated

- **Data Collection:** APIs, web scraping, data ingestion
- **Data Processing:** Cleaning, transformation, feature engineering
- **Statistical Analysis:** EDA, hypothesis testing, correlation analysis
- **Machine Learning:** Classification algorithms, model evaluation, hyperparameter tuning
- **Data Visualization:** Static and interactive visualizations
- **Business Analytics:** Translating technical findings to business insights

## 📝 Methodology

1. **Problem Definition:** Predict Falcon 9 first stage landing success
2. **Data Collection:** Multi-source data gathering (API + web scraping)
3. **Data Preprocessing:** Cleaning, feature engineering, transformation
4. **Exploratory Analysis:** Pattern discovery and insight generation
5. **Model Development:** Multiple algorithm comparison and optimization
6. **Evaluation:** Performance assessment and model selection
7. **Deployment:** Interactive dashboard for stakeholder engagement

## 🔮 Future Enhancements

- Real-time data pipeline integration
- Advanced feature engineering (weather data, rocket specifications)
- Deep learning model exploration
- Cost prediction modeling
- Competitor analysis integration

---

*This project was completed as part of the IBM Data Science Professional Certificate program on Coursera, demonstrating practical application of data science methodologies to real-world business problems.*