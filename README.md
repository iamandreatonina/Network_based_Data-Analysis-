# Network-Based Data Analysis course project

Project for the Network-Based Data Analysis course held by Professor Mario Lauria (A.Y. 2023-2024).

+ [Code](https://github.com/iamandreatonina/Network_based_Data-Analysis-/tree/main/Code)
+ [Report](https://github.com/iamandreatonina/Network_based_Data-Analysis-/tree/main/Report_%26_Presentation)


## Chosen disease 

Colorectal cancer (CRC), which includes both colon and rectal cancer, has become a significant health concern. It ranks as the third most commonly diagnosed cancer and the second leading cause of cancer-related deaths, accounting for approximately 9.4% of cancer-related deaths in 2020.

## Data utilized 

From Gene Expression Omnibus (GEO), the dataset [GSE110225](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE110225) (Vlachavas EI et al) was selected. 

## Aim and Workflow
    
This project aims to uncover new findings about Colorectal cancer (CRC) and seeks to advance the understanding of this tumor by establishing a set of variables capable of discriminating between cancer and normal samples. The workflow for this project can be summarized into three main steps:\
  * **Exploratory Analysis**: In the first part of the workflow, an exploratory data analysis was performed using unsupervised methods.
      * Principal Component Analysis (PCA)
      * K-means clustering
      * Hirechichal clustering
  * **Supervised Learning**: The second part involved utilizing supervised learning methods as classifiers to identify the most significant variables.
      * Random Forest
      * Linear Discriminant Analysis (LDA)
      * Lasso and Ridge regression
      * SCUDO (Signature-based Clustering for Diagnostic Purposes)
  * **Functional Enrichment Analysis**: Finally, it was used the important variables found in the previous step as inputs for various tools that perform Over-Representation Analysis and Network-based Analysis to identify enriched terms.
      * Over-Representation Analysis: gProfiler and DAVID
      * Network-based Analysis: pathfindR, EnrichNet and STRING
