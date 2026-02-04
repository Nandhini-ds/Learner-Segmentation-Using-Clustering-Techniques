# Learner Segmentation Using Clustering Techniques

## Business Problem

Scaler is an online tech-versity offering intensive computer science & Data Science courses through live classes delivered by tech leaders and subject matter experts. The meticulously structured program enhances the skills of software professionals by offering a modern curriculum with exposure to the latest technologies. It is a product by InterviewBit.

A significant challenge for Scaler is understanding the diverse backgrounds of its learners, especially in terms of their current roles, companies, and experience. Clustering similar learners helps in customizing the learning experience, thereby increasing retention and satisfaction. The goal is to use data-driven segmentation to support personalized learning strategies by comparing different clustering approaches such as K-Means and Hierarchical clustering.

## Objectives

* Segment learners based on their job profile, company, CTC, experience, and job position to create meaningful clusters.
* Identify the optimal number of clusters using the Elbow method.
* Compare K-Means and Hierarchical clustering approaches.
* Provide actionable business insights and recommendations based on learner segments.

## Tools & Technologies

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab

## Models Used

* K-means Clustering.
* Hierarchical Clustering

## Dataset:
## Dataset link: https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/002/856/original/scaler_clustering.csv
Column Name         Description
-------------------------------------------------------
Unnamed: 0          Index of the dataset
Email_hash          Anonymised personal identifiable information (PII)
Company_hash        Anonymized identifier for the company (current employer)
orgyear             Employment start year
CTC                 Current cost to company (salary)
Job_position        Job profile in the company
CTC_updated_year    Year in which CTC was last updated (increment/promotion)

## How to Run

Open the notebook `Scaler.ipynb` in Google Colab run all cells sequentially.

## Results & Recommendations

Detailed cluster analysis and business recommendations are provided in the notebook.
