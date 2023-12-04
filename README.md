# CMPE255 Dimensionality Reduction Assignment

## Dimensionality Reduction Techniques - [Colab](https://github.com/sjkchang/CMPE255-Dimensionality-Reduction/blob/master/DimensionalityReduction_1.ipynb)

The colab should cover cases where it works and where it does not works.
The colab should include: PCA, SVD, MDS, ISOMap, LLE, UMAP and t-sne

## Dimensionality Reduction then Clustering - [Colab](https://github.com/sjkchang/CMPE255-Dimensionality-Reduction/blob/master/DimensionalityReduction_2.ipynb)

Write a colab to illustrate how dimensionality reduction technique like umap can be used followed by clustering. (see slide show in clustering) as well as a classification feature extraction technique

## Databricks

#### Description of the Assignment Progress and Issue Encountered

As part of my assignment to demonstrate dimensionality reduction, I embarked on a project using Databricks, integrated with AWS, to analyze a chosen dataset. The dataset selected for this purpose was the Wine Quality dataset, well-regarded for its suitability in demonstrating key concepts of dimensionality reduction due to its various physicochemical properties and quality scores.

The initial stages of the project involved setting up the Databricks environment on AWS, a task that required careful configuration and understanding of both platforms. After successfully creating and configuring the Databricks workspace and cluster, my next objective was to upload the dataset into this environment for analysis.

To achieve this, I utilized the Data Ingestion functionality of Databricks, which is specifically designed to streamline the process of importing data into the platform. The Wine Quality dataset was sourced and prepared for upload, following the appropriate procedures to ensure its correct integration into the Databricks File System (DBFS).

The data upload process was executed smoothly, and I was able to successfully ingest the dataset into the Databricks environment. The next steps would have involved preprocessing this data and applying a dimensionality reduction technique, such as Principal Component Analysis (PCA), to extract meaningful insights and patterns from the dataset.

However, an unforeseen issue arose at this juncture. An error occurred related to the integration of Databricks with my AWS account, which led to an abrupt halt in the project's progress. This error manifested as a disruption in the Databricks cluster, preventing it from running further and effectively halting my ability to conduct any data analysis.

Despite efforts to resolve this issue, the nature of the error, stemming from the interaction between Databricks and AWS, proved to be a significant obstacle. As a result, I was unable to complete the dimensionality reduction part of the assignment as originally planned.

The challenge faced highlights the complexities and potential issues that can arise when working with sophisticated cloud-based data platforms and tools. This experience has provided valuable insights into the importance of contingency planning and troubleshooting in data science projects, especially those that rely on the integration of multiple cloud services.
