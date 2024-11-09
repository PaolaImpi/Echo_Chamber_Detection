# Comparing Echo Chamber Detection Metrics: A Cross-modeling and Cross-platform Analysis of Twitter and Reddit

This project provides a comprehensive comparative analysis of the primary echo chamber detection metrics proposed in the literature. These metrics include network analysis, content analysis, and hybrid approaches. The focus is on their application in a cross-platform context involving Twitter (now renamed X) and Reddit. Through this analysis, the project uncovers the distinct dynamics of echo chambers across these platforms, evaluates the strengths and limitations of the various metrics, and assesses their applicability across different social graph modeling approaches and domains.



## Datasets Used

* **Garimella Dataset**: Edgelists for the retweet networks (ukraine, beefban, gunsense, ultralive, and nationalkissingday) are [publicly available](https://github.com/gvrkiran/controversy-detection/tree/master/networks/retweet_networks).
* **Vaccination Twitter Dataset**: Available on [Kaggle](https://www.kaggle.com/keplaxo/twitter-vaccination-dataset).
* **Reddit Dataset**: Raw data can be accessed through the Reddit API using the "Scraping_Reddit" notebook available in the Data folder, where you can set your own Reddit credentials. The IDs of the considered Reddit posts, for each graph, are also available in the Data folder.



## Folder Structure

* **Data**: Contains the datasets used in the project. This folder also includes the "Scraping_Reddit" notebook, which allows you to collect Reddit data using the Reddit API, along with the IDs of the considered Reddit posts for each graph.


* **Modeling Graphs**: Contains notebooks for constructing and analyzing social media graphs, including graph building, partitioning for community detection, sentiment analysis, and topic modeling.

* **Metrics**:  Includes code for calculating and analyzing the various echo chamber detection metrics.
