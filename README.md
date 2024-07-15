# Intel Products Sentiment Analysis from Online Reviews

## Problem Statement 11

### Category
- Artificial Intelligence
- Machine Learning
- Software Engineering

### Prerequisites
- Machine Learning & Natural Language Processing
- Python Programming Language
- ETL (Extract, Transform, Load) Knowledge

### Description
Intel Products are reviewed by end users and tech reviewers on various platforms. The objective of this project is to scrape the reviews available on different sources over the last 3-5 years. Using various exploratory data analysis, machine learning, and natural language processing techniques, we aim to:
1. Determine the sentiments of the reviews.
2. Cluster affinity reviews.
3. Identify trends in sentiments over time.
4. Extract features and keywords associated with specific sentiments.
5. Provide recommendations for key improvements based on user reviews for future products.
6. Ensure sentiments and other analyses are demonstrated across different product categories.

### Outcomes
- Provide models and outputs for the above use cases along with performance metrics for each model.
- Share the data sources, as well as the train and test datasets, upon project completion.
- Deliver key summary and recommendation slides based on the analysis and model outcomes.

### Project Structure
intel-sentiment-analysis/
│
├── data/
│ ├── raw/
│ ├── processed/
│ ├── train/
│ └── test/
│
├── notebooks/
│ ├── data_exploration.ipynb
│ ├── sentiment_analysis.ipynb
│ ├── clustering_analysis.ipynb
│ ├── trends_analysis.ipynb
│ └── feature_extraction.ipynb
│
├── src/
│ ├── data/
│ │ ├── scraping.py
│ │ ├── preprocessing.py
│ │ └── etl.py
│ │
│ ├── models/
│ │ ├── sentiment_model.py
│ │ ├── clustering_model.py
│ │ └── trends_model.py
│ │
│ └── utils/
│ ├── helpers.py
│ └── metrics.py
│
├── reports/
│ ├── key_summary.pdf
│ ├── recommendations.pdf
│ └── performance_metrics.pdf
│
├── .gitignore
├── README.md
└── requirements.txt


### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Aayushkr2574/Team-Pandavs-Intel-Unnati-Industrial-Training--Intel-Product-Sentiment-Analysis-.git
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Usage
1. **Data Scraping**: To scrape data, run:
    ```bash
    https://github.com/Aayushkr2574/Team-Pandavs-Intel-Unnati-Industrial-Training--Intel-Product-Sentiment-Analysis-/blob/main/Web%20Scraping%20code.ipynb
    ```
2. **Data Preprocessing**: To preprocess the scraped data, run:
    ```bash
    https://github.com/Aayushkr2574/Team-Pandavs-Intel-Unnati-Industrial-Training--Intel-Product-Sentiment-Analysis-/blob/main/Translation%20code.ipynb
    ```
3. **Model Training and Evaluation**:
    - Sentiment Analysis:
        ```bash
        https://github.com/Aayushkr2574/Team-Pandavs-Intel-Unnati-Industrial-Training--Intel-Product-Sentiment-Analysis-/blob/main/sentiment%20code.ipynb
        ```
    

### Contributions
Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or enhancements.

### License
This project is licensed under the MIT License. See the (https://github.com/Aayushkr2574/Team-Pandavs-Intel-Unnati-Industrial-Training--Intel-Product-Sentiment-Analysis-/blob/main/LICENSE) file for more details.

### Contact
For any questions or suggestions, please contact (mailto:aayush2574@gmail.com).
