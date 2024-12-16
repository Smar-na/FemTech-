# FemTech

This repository focuses on scraping app reviews, ratings, and metadata to analyze women-centric apps (FemTech). It enables insights into user feedback, app usability, and the alignment of app design with feminist HCI and design justice principles.

---

## **Project Overview**

- **Purpose**: Collect, clean, and analyze app review data for research purposes.  
- **Goal**: Generate clean datasets and key insights to understand user-centric features and marginalized user needs.  
- **Focus Areas**:  
   - Scraping app reviews, ratings, and metadata.  
   - Text and statistical analysis of app feedback.  
   - Insights into design principles for FemTech apps.  

---

## **Repository Contents**

### **1. App_scrape.ipynb**  
- **Purpose**: Scrapes app reviews, ratings, and metadata from app platforms.  
- **Features**:  
  - Extracts review text, numeric ratings, and app details.  
  - Saves the scraped data in a clean **CSV format** for further analysis.  
- **Dependencies**:  
  - Python libraries: `requests`, `beautifulsoup4`, `pandas`.  

---

### **2. Code for app scraping and EDA.ipynb**  
- **Purpose**: Combines app scraping and performs **Exploratory Data Analysis (EDA)**.  
- **Features**:  
  - Scrapes app data.  
  - Cleans the dataset (removing duplicates, handling missing values).  
  - Visualizes key metrics (e.g., rating distributions, trends over time).  
- **Dependencies**:  
  - Python libraries: `pandas`, `matplotlib`, `seaborn`, `requests`.  

---

### **3. UNI, BI, TRIGRAMS.ipynb**  
- **Purpose**: Analyzes app review text using **n-grams** to find common word patterns.  
- **Features**:  
  - Generates:  
    - **Unigrams** (single words)  
    - **Bigrams** (two-word combinations)  
    - **Trigrams** (three-word combinations).  
  - Identifies frequently used phrases in user reviews.  
- **Dependencies**:  
  - Python libraries: `nltk`, `pandas`, `collections`.  

---

### **4. Descriptive_stats_for_apps.ipynb**  
- **Purpose**: Computes descriptive statistics for app review datasets.  
- **Features**:  
  - Summarizes:  
    - Rating distributions (mean, median, mode).  
    - Text length and word count statistics.  
  - Generates insights for user-centric features and app performance.  
- **Dependencies**:  
  - Python libraries: `pandas`, `numpy`, `matplotlib`.  

---

## **🚀 Getting Started**

Follow these steps to set up and run the project on your local machine.

### **1. Clone the Repository**
First, download the project to your system.

git clone https://github.com/<Samar-na>/<Femtech>
cd <Femtech>

## **Install Dependencies**

Ensure you have the required libraries installed. Run the following command:
!pip install pandas requests beautifulsoup4 matplotlib seaborn nltk numpy

Alternatively, you can install libraries one by one:

pandas: For handling and exporting data.
requests: For fetching app webpage data.
beautifulsoup4: For parsing and scraping web content.
matplotlib and seaborn: For visualizations.
nltk: For n-gram analysis.
numpy: For numerical operations.
If using Google Colab, these libraries are pre-installed.

## **Run the Notebook**

Open Jupyter Notebook on your system or Google Colab. Load the relevant notebook:

File: eg:App_scrape.ipynb
Update the scraping configuration (provide app page URL or relevant inputs).
Run the cells step by step.

📊 How It Works & Output

### **1. App_scrape.ipynb**

How It Works:

Fetch the Webpage:

The requests library retrieves the HTML content of app review pages.

Parse Content:

BeautifulSoup parses the HTML and extracts key elements:

Review content (text of user reviews).
Ratings (numeric star ratings).
Date of review submission.

Data Cleaning:

Cleans the data by removing irrelevant or missing information and ensures the reviews are ready for analysis.

Save as CSV:

The cleaned reviews, ratings, and metadata are saved into a structured CSV file.

#### **Output:**

CSV File:
The resulting CSV file contains:
Review Content: User reviews.
Ratings: Star ratings (1-5).
Date: Date of the review.
Other metadata based on the app source.

### **2. Code for app scraping and EDA.ipynb**

How It Works:

Scrape Data:

Uses the same scraping method as App_scrape.ipynb to retrieve app reviews and metadata.

Clean Data:

Processes the scraped data to handle missing entries, duplicates, and irrelevant information.

Exploratory Data Analysis (EDA):

It generates various visualizations, such as:

Rating distribution (histograms or bar charts).
Rating trends over time (time-based graphs).
Review frequency across different apps.

Visualization:

The notebook visualizes insights using matplotlib and seaborn.

#### **Output:**

CSV File:

Contains the cleaned reviews and ratings data.

Visualizations:

Rating distribution chart.
Review frequency analysis over time.
Common themes and user satisfaction trends.

### **3. UNI, BI, TRIGRAMS.ipynb**

How It Works:

Text Preprocessing:

The review content is tokenized into words (unigrams) using the nltk library.


N-gram Generation:

It generates unigrams (single words), bigrams (pairs of words), and trigrams (triplets of words).

Frequency Analysis:

It computes the frequency of n-grams (unigrams, bigrams, trigrams), identifying common words, pairs, and triplets.

Insights:

The most frequent n-grams provide insights into common themes and phrases in the reviews.

#### **Output:**

Frequency Lists:

A list of the most common unigrams, bigrams, and trigrams.
Insights into recurring patterns or themes in the reviews.


### **4. Descriptive_stats_for_apps.ipynb**

How It Works:

Data Import:

Imports the cleaned dataset from App_scrape.ipynb or Code for app scraping and EDA.ipynb.

Descriptive Statistics:

Calculates basic statistics such as:

Mean, Median, Mode of the ratings.
Rating distribution (number of reviews for each rating).
Review content statistics (average length of reviews, etc.).

Visualization:

Uses matplotlib and seaborn for visualizing statistics like:

Rating distribution charts.
Review length distribution (histograms).

#### **Output:**

Descriptive Statistics:
Rating summary (mean, median, mode).
Distribution of ratings.
Average review length and common terms.

Visualizations:
Rating distribution (bar charts).
Review length distribution (histograms).

## **📝 Usage**

** App_scrape.ipynb**

Use the generated CSV for further analysis of user satisfaction and app performance.

** Code for app scraping and EDA.ipynb **

Visualizations such as rating distribution and review frequency trends will help you analyze user satisfaction and app performance.

** UNI, BI, TRIGRAMS.ipynb **

The notebook will output a frequency list of common words, pairs, and triplets used in the reviews.
Analyze the results to identify recurring themes and patterns within the app reviews.

**Descriptive_stats_for_apps.ipynb **

Visualizations such as rating distribution and review length histograms will be generated for analysis.
Use the output to gain insights into user sentiment and the overall app performance.

## **📜 License**
This project is licensed under the MIT License. See the LICENSE file for details.

## **🤝 Contributions**
Contributions are welcome!

Fork the repository.
Create a feature branch.
Submit a pull request for review.

## **✨ Contact**
For any questions or collaboration opportunities, reach out:

Your Name: smarana.1947@gmail.com
GitHub Profile: Liki-py
