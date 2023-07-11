# Ads-Effect-Analysis
This is a collaborative application project with a company aimed at conducting impact analysis on product advertisements. By utilizing web crawlers to gather sufficient information, we will establish a DID model using similarity matching methods and calculate the influence of advertisements on product sales. 

Due to data security concerns, we are unable to upload the source data.

# Notebook List
## 01 DataCleaning
This Jupyter notebook is primarily focused on data cleaning. The data is derived from two main sources: Sales and Ads. Each dataset undergoes a series of cleaning steps, resulting in a refined dataset ready for further analysis. 

## 02 Amazon-Webscrape
The primary objective of this Jupyter notebook is to scrape data from the Amazon website. The targeted data includes Category, rating, and ratings for products from their respective Amazon categories. The Selenium library is employed throughout the scraping process to simulate browser behavior, including opening web pages, finding elements, and reading element content.

## 03 Model
The focus of this Jupyter notebook is the establishment of a Difference-in-Differences (DID) model. The model building process includes:
1. Classic DID: Establishing a basic Difference-in-Differences model.
2. Staggered DID: Implementing a staggered version of the Difference-in-Differences model.
3. PSM-DID: Performing Propensity Score Matching along with Difference-in-Differences.
   For similarity calculation, two methods are used: manual calculation using Manhattan and Jaccard distances, as well as machine learning techniques like logistic regression and k-nearest neighbors (k-NN).
4. Robustness Test: Conducting robustness checks on the model to ensure the reliability of the results.
5. Interactive Model: Building an interactive version of the model for an enhanced user experience.
