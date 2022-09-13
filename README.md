# Diversifying top-k search results

This repository consists of 3 code files:

1. Preprocessing_OHSUMED_test_collection.ipynb - This Jupyter notebook contains the code to read OHSUMED test collection and convert it to appropriate json format for further processing.

2. Fetching_top_k_results_and_building_adjacency_matrix.ipynb - This Jupyter notebook contains the code to fetch top-k results from Apache SOLR along with the relevance scores and build the adjacency matrix for every query in the test collection.

3. Applying_community_detection.rmd - This R Markdown file uses igraph R package to detect clusters of documents in top-k retrieved results. The knit pdf version is available as Applying_community_detection.pdf.
