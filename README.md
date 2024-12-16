# FemTech-App Scraping for FemTech Analysis

This project focuses on scraping app reviews, ratings, and metadata to analyze women-centric apps (FemTech) for research purposes. The notebook extracts data from app platforms, cleans it, and prepares it for further analysis, enabling insights into user feedback, app usability, and design justice principles.

**Project Overview**

Purpose: To scrape app reviews and related data for FemTech apps.
Goal: Provide a clean dataset (CSV format) for further analysis of user experiences and feedback.
This project aligns with feminist HCI and design justice principles, focusing on analyzing user-centric features and attention toward marginalized needs.

**Features**

Scrapes app reviews, ratings, and metadata.
Saves the scraped data in a CSV file.
Handles text and numeric data for clean analysis.
Repository Contents
App_scrape.ipynb: The main Jupyter Notebook for scraping app reviews and ratings.
Dependencies: Required Python libraries for scraping and handling data.

**🚀Getting Started**

Follow these steps to set up and run the project on your local machine.

**1. Clone the Repository**

First, download the project to your system.

bash
Copy code
git clone https://github.com/<Smar-na>/<App_scrape.ipynb>
cd <App_scrape.ipynb>

**2. Install Dependencies**

Ensure you have the required libraries installed. Run the following command:

bash
Copy code
pip install pandas requests beautifulsoup4
Alternatively, you can install libraries one by one:

pandas: For handling and exporting data.
requests: For fetching app webpage data.
beautifulsoup4: For parsing and scraping web content.

**3. Run the Notebook**

Open Jupyter Notebook on your system or Google Colab.
Load the notebook:
File: App_scrape.ipynb
Update the scraping configuration:
Add the app page URL or relevant inputs where required.
Run the cells step by step.

**📊 Output**

The notebook generates:

CSV File: Contains scraped app reviews, ratings, and other metadata.
Data Columns:
Review Content: User reviews.
Ratings: Star ratings (1-5).
Date: When the review was posted.
Additional metadata depending on the app source.

**🧰 Dependencies**

Here’s a list of required Python libraries:

pandas
requests
beautifulsoup4
re (built-in for regex operations)
If using Google Colab, these libraries are pre-installed.

**⚡ How It Works**

Fetch the Webpage: The requests library retrieves the app review webpage.
Parse Content: The BeautifulSoup library parses the webpage and extracts key elements like:
Review text
Ratings
Dates
Clean Data: Handles missing or irrelevant information for a clean dataset.
Save as CSV: Exports the reviews and ratings to a structured CSV file.

**📝 Usage**

Use the resulting CSV file to analyze:
User satisfaction (based on ratings).
Common themes in reviews (using n-grams or sentiment analysis).
Combine with other notebooks like EDA or descriptive statistics for deeper insights.

**📜 License**

This project is licensed under the MIT License.

**🤝 Contributions**

Contributions are welcome!

Fork the repository.
Create a feature branch.
Submit a pull request for review.

**✨ Contact**

For any questions or collaboration opportunities, reach out:

Your Name: likithareddy.yk@gmail.com
GitHub Profile: Smar-na
