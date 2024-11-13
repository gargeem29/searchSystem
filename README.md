# Search System

## Project Description
This project implements a search system in Python, designed to process and retrieve relevant information from a dataset based on specific search criteria. The notebook covers data preprocessing, feature extraction, and search algorithms to facilitate accurate and efficient search operations.


## How to Run
1. Clone the repository
2. Open the notebook in GoogleColab and execute the cells one by one

## Features
- **Data Preprocessing**: Cleans data for consistency and prepares it for further processing.
- **Feature Engineering**: Extracts meaningful features from the text data to enhance search functionality.
- **Search Algorithm**: Uses similarity measures to return relevant search results based on a query.


## Data Loading and Preprocessing
Load your dataset (eg: I uploaded movies.csv), inspect it, and clean it by removing null or missing values

## Feature Engineering
This transform text data into numerical representations using CountVectorizer. This process helps convert text information into vectors, which are necessary for similarity calculations

## Search Algo Implementation 
This implements a search function using cosine similarity. Cosine similarity measures the angle between two vectors (in this case, text vectors), allowing us to rank the relevance of documents to a query.


## Installation
Ensure you have Python 3.x installed. Install the required libraries with:
```bash
pip install numpy pandas scikit-learn





![image](https://github.com/user-attachments/assets/8e5f8b8a-b91b-4730-beea-0f7fb30a1cbf)





