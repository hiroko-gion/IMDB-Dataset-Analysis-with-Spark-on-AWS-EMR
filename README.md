
# IMDB Dataset Analysis with Spark on AWS EMR





## Introduction
This project involves the analysis of IMDB datasets sourced from Kaggle using Spark on Amazon Web Services' Elastic MapReduce (EMR) platform. The aim is to derive insights and perform data analytics on a large-scale dataset leveraging PySpark's DataFrame API capabilities.


## Project Scope
### Infrastructure Provisioning
1. **Provisioning a Spark cluster on AWS EMR**:
    Utilized Amazon Web Services' Elastic MapReduce (EMR) platform to provision a Spark cluster, enabling distributed data processing capabilities.
2. **Integration of the cluster with a Jupyter Notebook**:
    Seamlessly integrated the Spark cluster provisioned on AWS EMR with a Jupyter Notebook environment. This integration facilitated interactive data analysis and visualization.
3. **Retrieval of IMDB data from a publicly available S3 bucket**:
    Retrieved the IMDB datasets from a publicly available S3 bucket on AWS. This approach ensured seamless access to the dataset within the Spark cluster for analysis.
4. **PySpark**
    PySpark, the Python API for Apache Spark, served as a primary tool for data analysis. It provided access to Spark's powerful DataFrame API and Spark SQL functionalities, enabling efficient processing and analysis of large-scale datasets.
   
### Analysis Tasks
1. Initial Setup:
- Importing necessary dependencies (pandas and matplotlib)
- Loading the IMDB dataset into a PySpark DataFrame
2. Genres Analysis:
- Denormalize genres associated with titles and conduct basic analysis
- Build a horizontal bar chart of top genres
3. Job Categories Analysis:
- Identifying top job categories within the dataset
- Build a bar chart of top job categories
4. Answering Key Questions:
Addressing specific inquiries related to actors, movies, ratings, and genres.
- What are the movies in which both Johnny Depp and Helena Bonham Carter have acted together?
- What are the movies in which Brad Pitt has acted since 2010?
- How many movies has Zendaya acted in each year?
- Which movies, released in 2019, have an average rating exceeding 9.7?
- Among the titles in which Clint Eastwood and Harrison Ford have acted, who has the higher average rating?
- What is the movie(s) with the highest average rating among those in which Chris Evans has acted?
- What is the percentage of adult titles in which actors and actresses have acted?
- What are the top 10 movie genres with the shortest average runtime?
- What are the most common character names for actors and actresses in Romance movies?



## Analysis Results
### Genre Analysis
- **Genre Distribution:** Reveals the prevalence of different movie genres in the dataset, highlighting the most common and least represented genres.
- **Genre Relationships:** Explores relationships between genres, showcasing co-occurrences and potential patterns in movie categorizations.
### Job Categories Analysis
- **Top Job Categories:** Identifies the most frequent job categories within the dataset, shedding light on the roles that contribute significantly to movie production.
### Key Questions Answered
- **Actor Collaborations:** Lists movies where specific actors have collaborated, offering insights into their shared projects
- **Rating Analysis:** Provides movies released in 2019 with exceptionally high ratings (> 9.7), as well as the average ratings for movies involving certain actors
- **Character Name Analysis:** Lists the most common character names for actors and actresses in Romance movies

## Conclusion
This project demonstrates adeptness in:
 - **AWS EMR Infrastructure Setup:** Proficiently configuring and setting up infrastructure on AWS EMR, showcasing the ability to provision a Spark cluster and integrate it with the necessary tools.
- **Effective PySpark Data Analysis:** Utilizing PySpark effectively to perform comprehensive data analysis, leveraging its DataFrame API and Spark SQL functionalities to process and derive insights from extensive IMDB datasets.
- **Insightful Data Extraction:** Extracting meaningful and actionable insights from the vast IMDB datasets, showcasing the ability to derive valuable information regarding movie genres, job categories, actor collaborations, and ratings.
