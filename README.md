# Community Detection in Financial Markets

The rapid growth of data generation in today's world has given rise to numerous challenges, particularly in handling and extracting meaningful insights from large datasets. This project, undertaken as part of the "Hardware and Software for Big Data" course, delves into the intricate landscape of community detection in financial markets. The objective is to develop a robust community detection algorithm that unveils subsets of stocks sharing similar behaviors, contributing to a deeper understanding of market dynamics. This endeavor is approached with a focus on harnessing the capabilities of Spark with Python and Kafka as a stream processor. The integration of these technologies sets the stage for an efficient and scalable solution to address the inherent challenges posed by big data in the financial domain.

## Project Implementation Steps:

1. **Identifying and Importing Necessary Packages**
   - Identified and imported essential Python packages crucial for the successful implementation of the community detection algorithm.

2. **Downloading Historical Data for 89 Stocks using yfinance**
   - Successfully downloaded historical data for 89 stocks using the yfinance library.

3. **Kafka Topic Creation for Each of the 89 Stocks**
   - Crafted individual Kafka topics for each of the 89 stocks previously identified.

4. **Utilizing Kafka Producer to Populate Topics for 89 Stocks**
   - Employed a Kafka producer to actively write data into the individual topics created for each of the 89 stocks.

5. **Saving Stock Datasets Locally in XLSX Format**
   - Focused on persisting financial datasets for the identified 89 stocks locally in an XLSX format.

6. **Preprocessing Financial Datasets for Analysis**
   - Conducted essential preprocessing steps on the financial datasets for the identified stocks.

7. **Scaling Selected Columns for Standardized Analysis**
   - Focused on scaling selected columns within the financial datasets to ensure standardized values for analysis.

8. **Integration of Scaled Features: Creating a Combined DataFrame**
   - Seamlessly integrated scaled features from individual stock DataFrames into a consolidated dataset.

9. **Sparking Insight: Establishing a Spark Session for Enhanced Data Processing**
   - Initiated a Spark session using the pyspark.sql module for advanced data processing.

10. **Unveiling Patterns: Implementing K-Means Clustering for Insightful Stock Grouping**
    - Employed K-Means clustering to unravel inherent patterns and group stocks based on their features.

11. **Visualizing Stock Clusters: A Glimpse into K-Means Results**
    - Employed visualization techniques to provide a clear and insightful representation of the stock clusters formed through the K-Means algorithm.

12. **Unveiling Connections: Constructing a Correlation-Based Graph**
    - Delved into the intricate relationships between stocks by constructing a graph based on correlation coefficients.

13. **Deciphering Financial Networks: Community Detection Analysis**
    - Applied the Girvan-Newman algorithm to unravel communities within the constructed financial graph.

14. **Gauge of Interconnectedness: Analyzing Clustering Coefficients**
    - Delved into the interconnectedness of the financial network by calculating the clustering coefficient for each node.

15. **Evaluating Community Separability: A Quantitative Measure**
    - Introduced a custom separability metric to quantify the distinctiveness between identified communities within the financial network.

16. **Assessing Network Structure: Fractions over Median Degree Analysis**
    - Introduced a key metric, 'Fractions over Median Degree,' to assess the network structure within identified communities.

17. **Network Quality Metrics: Conductance, Normalized Cut, Cut Ratio Analysis**
    - Delved into the quality metrics of the financial network by calculating Conductance, Normalized Cut, and Cut Ratio for each identified community.
