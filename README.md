# DataScienceFinalProject
# EECS-731-News-Muse
EECS731 Semester Project

## Abstract:
  Our project will be focused on applying various data science approaches on fake news. Fake news is a falsified article or story intended to mislead the audience. People or online bots use manipulated news content as a tool to spread propaganda, influence a network of people, and to gain socio-political or economic benefits. Additionally, owing to its inherent dynamics, social media has become a fertile ground for spreading fake news.
  
  However, we believe that a piece of news is at its core, a piece of data. And, using a data science lifecycle effectively, we can identify fake news and formulate methods to determine its impact from the spatiotemporal and social metadata. At first, we can perform some exploratory data analysis to get an idea about the context or distribution of the content. Then, we can preprocess the data and work on identifying or generating suitable features from the news text and the metadata. Eventually, we can harness powerful classical and modern classification, clustering, and regression techniques to reveal information from the data that would otherwise be hidden initially. Finally, we can evaluate the performance of our data science pipeline both quantitatively and qualitativel
  
## Datasets:
1. Kaggle Fake News Dataset: https://www.kaggle.com/c/fake-news/data
2. FakeNewsNet (Twitter content): https://github.com/KaiDMML/FakeNewsNet
3. Fakeddit (Reddit content with text and images): https://github.com/entitize/Fakeddit

## Folder structure:
### data - This folder has the datsets that were used in this project
1. data\external\Fake-News-Dataset 		- Fake news dataset
2. data\external\OnlineNewsPopularity 	- Online news popularity dataset 
3. data\processed\kaggle_features		- Combined processed features dataset

### docs - This folder has the reports
1. EECS731_Proposal_FakeNews			- Initial project proposal
2. EECS 731_Project Presentation		- Project presentation
3. EECS 731_Project report_News Muse	- Project report 

### notebooks - This folder has the code in the form of Jupyter notebooks 
1. FakeNewsDetector 					- Fake new classifier
2. NewsPopularity						- Online news popularity classfication, PCA and clustering
3. Kaggle_Featureextractions_clustering	- Feature extration and combining two datasets 
4. NewsPopularity_Regression			- Online news popularity regression and domain adaptation
