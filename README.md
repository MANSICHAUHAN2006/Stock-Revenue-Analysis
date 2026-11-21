# 📊 Stock Market & Revenue Analysis Using Python

## 🚀 About the Project

This project focuses on extracting, analyzing, and visualizing historical stock market data and quarterly revenue of **Tesla and GameStop** using Python.

The main objective is to understand how stock prices and company revenue change over time by collecting financial data from different sources and presenting the results through data visualizations.

This project is based on the IBM Data Analysis with Python learning project.

## 🎯 Project Objectives

- Collect historical stock market data using Python.
- Extract quarterly revenue data through web scraping.
- Process and clean financial datasets.
- Analyze historical stock prices and revenue.
- Create visualizations to understand financial trends.
- Practice real-world data analytics techniques.

## 🏢 Companies Covered

| Company | Stock Symbol |
|---|---|
| Tesla | TSLA |
| GameStop | GME |

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Code execution and analysis |
| Pandas | Data manipulation and cleaning |
| yfinance | Stock market data extraction |
| Requests | Fetching webpage content |
| BeautifulSoup | Web scraping |
| Matplotlib | Data visualization |

## 📂 Project Workflow

### 1. Stock Data Extraction
- Used the `yfinance` library to retrieve historical stock data.
- Extracted Tesla and GameStop stock information.
- Stored the results in Pandas DataFrames.

### 2. Revenue Data Collection
- Retrieved quarterly revenue information from web pages.
- Used Requests to fetch HTML content.
- Used BeautifulSoup to extract relevant financial tables.

### 3. Data Cleaning
- Removed dollar signs and commas from revenue values.
- Removed missing and empty values.
- Prepared datasets for analysis and visualization.

### 4. Data Visualization
- Created a reusable graphing function using Matplotlib.
- Visualized historical stock prices.
- Visualized quarterly company revenue.
- Compared stock price and revenue trends for both companies.

## 📈 Analysis & Visualizations

The project includes the following visualizations:

**Tesla Analysis**
- Historical Tesla stock price.
- Tesla quarterly revenue.

**GameStop Analysis**
- Historical GameStop stock price.
- GameStop quarterly revenue.

The visualizations use historical data up to June 2021 for stock prices and April 2021 for revenue.

## 📁 Repository Structure

```text
Stock-Revenue-Analysis/
│
├── [Revenue Data and Building a Dashboard.ipynb)
│
└── README.md
```

## ⚙️ Installation & Execution

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Stock-Revenue-Analysis.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Stock-Revenue-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install yfinance pandas requests beautifulsoup4 matplotlib
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

`Tesla and GameStop Stock & Revenue Analysis.ipynb`

Run the cells sequentially to execute the analysis.

## 📚 Key Learnings

By completing this project, I gained practical experience in:

- Python programming for data analysis.
- Working with financial data.
- Extracting data using Python libraries.
- Web scraping using BeautifulSoup.
- Data cleaning and manipulation with Pandas.
- Creating visualizations using Matplotlib.
- Understanding historical stock market trends.

## 🔮 Future Improvements

- Extend the analysis to additional companies such as Amazon and AMD.
- Implement interactive visualizations using Plotly.
- Develop an interactive financial analytics dashboard.
- Add more financial metrics for deeper analysis.

## ⚠️ Disclaimer

This project is developed for educational and learning purposes only. The analysis is based on historical financial data and should not be considered investment advice.

## 👩‍💻 Author

**Mansi Chauhan**

Computer Engineering Student

---

⭐ If you find this project interesting, feel free to explore the repository!
