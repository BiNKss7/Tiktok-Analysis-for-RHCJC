# Tiktok-Analysis-for-RHCJC
This project was created to encourage the Roy Howard Community Journalism Center (RHCJC) to focus resources on one of the fastest-growing platforms: TikTok.
As part of this work, I analyzed the performance of other journalism centers on TikTok and used their results as benchmarks to forecast our own potential reach and engagement. The analysis also explores key factors that influence content performance, including:

Posting time (which hours and days drive the most views)

Video duration (how length affects engagement)

Posting frequency (how often to post for optimal reach)

The dataset was scraped from TikTok.com using the third-party scraping service Apify. It covers videos posted in the year 2025 (up to August).

The findings are meant to guide decision-making around maximizing the reach, engagement, and overall performance of content we post on TikTok.



**Repurpose:**

You are free to use my code for your own analysis. 

To rerun this analysis on your own machine:

**Clone the repository**

git clone https://github.com/BiNKss7/Tiktok-Analysis-for-RHCJC.git

cd your-repo-name


**Create a virtual environment (optional, but recommended)**

python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows


**Install dependencies**

pip install -r requirements.txt


**Launch Jupyter Notebook**

jupyter notebook


Then open the analysis notebook (e.g., tiktok_analysis.ipynb).

**Data**

The dataset was scraped using Apify
 from TikTok.com.

For this repo, the dataset used covers TikTok posts in 2025 (up to September).

If you want to update the dataset, you can scrape again with Apify or replace the CSV/JSON file in the data/ folder.

**Run the notebook**

Execute the cells in order to reproduce the analysis of posting times, video duration, posting frequency, and performance forecasting.

Visualizations are generated with Plotly and can be exported if needed.
