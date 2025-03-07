# Ace the Space

### Project Overview

This project builds a resume scoring and job recommendation system that matches resumes to relevant job descriptions using ****BERT embeddings**** for semantic text representation. It preprocesses resumes and job descriptions with NLP techniques, calculates similarity scores, and recommends the top 3 job matches based on cosine similarity.

The model is evaluated using ****accuracy**** and ****precision****, and a ****Random Forest Classifier**** predicts job titles for resumes. This solution efficiently pairs candidates with suitable job opportunities.
#
### Procedure Overview

#### 1. Exploratory Data Analysis (EDA)
Our EDA consisted of:

1. ***Text Length Distribution***
   - It calculates the length of resumes and job descriptions (number of words) and plots histograms of the distributions.
This will give an idea of how long the text data is in each column.

3. ***Word Clouds***
   - It generates a word cloud for both resumes and job descriptions using the WordCloud library.
This will give a visualize look of the most frequent words in both datasets.

5. ***Skills Count***:
    - It computes the number of skills mentioned in each resume and job description and prints the statistical summary for each.

7. ***Data types and descriptive statistics***
   - Understanding the structure of both the dataset.

#### 2. Feature Engineering
Feature Engineering for Resume Scoring and Job Recommendation System:

1. ***Text Preprocessing***: 
   - Applied ****tokenization****, ****lowercasing****, ****stopword removal****, and ****lemmatization**** to clean and standardize both resumes and job descriptions.

2. ***BERT Embeddings***: 
   - Used **BERT** to generate contextualized embeddings for both resumes and job descriptions, representing them as fixed-size vectors for deeper semantic understanding.

3. ***Cosine Similarity***: 
   - Calculated ****cosine similarity scores**** between resume embeddings and job description embeddings to measure and rank the relevance of job recommendations.

4. ***Combined Skills***: 
   - Merged the ****skills**** from both resumes and job descriptions into a single feature for better matching.

5. ***Top 3 Job Recommendations***: 
   - Extracted the ****top 3 unique job recommendations**** based on the highest similarity scores to ensure diverse and relevant job matches.
#
### Data Visualizations
![d1](https://github.com/user-attachments/assets/c87cf629-c350-4e63-b290-2be5a468a426)
![d2](https://github.com/user-attachments/assets/737b0848-b033-4bf7-b797-cb4da6d5e587)
![d3](https://github.com/user-attachments/assets/0e43af86-89d3-4b8e-8ecf-f1750d910027)
![d4](https://github.com/user-attachments/assets/6109a8c4-0197-4bda-92e6-acf7d90479d7)
