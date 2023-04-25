# Regex-based-Labeling-for-Text-Data
This solution generates enhanced class labels for user provided unlabeled text data.

## Product Overview

This solution helps create large training datasets without manually labeling them over weeks or months. It uses weak supervision approach and regular expression based heuristics with the help of labeling functions (LFs) to assign labels to unlabeled training data. The labels are further enhanced using confidence learning methodologies to provide clean labeled datat as output. The output contains a CSV file consisting of the text, regular expression based base labels and enhanced clean labels. The solution is beneficial for obtaining automated clean class labels for input text datasets with less manual effort.

## Product Highlight 

* This solution leverages data-centric approach to get better class labels. This is extremely pertinent for downstream supervised model building. One can use this solution in domains such as  e-commerce, marketing and fintech companies to automate the labeling of unlabelled text classification problems such as sentiment classification for product reviews, tweets or social media posts, finance news etc.
* The current solution only works with dataframes as input and generates output that contains only those data points that are labeled by the labeling function. It does not include any data points that have not been assigned any base label. For better results, we recommend upto 700 words in each row.
* PACE - ML is Mphasis framework and methodology for end-to-end machine learning development and deployment. PACE-ML enables organizations to improve the quality & reliability of the machine learning solutions in production and helps automate, scale, and monitor them. Need customized Machine Learning and Deep Learning solutions? Get in touch!

## Amazon Marketplace Link
The product can be found [here](https://aws.amazon.com/marketplace/pp/prodview-jhqk4od5efdzo).
