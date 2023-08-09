# Network Analysis and Prediction on Tennis Dataset
The following project involves Network Analysis and Prediction on the Tennis Dataset. The project intends to apply various Network Analysis tools including Centrality Analysis, Degree Distributions, Density Analysis, Community Detection and Link Prediction. Tools utilised for this project include Python and Gephi. The project was done in several parts as described below:

1. **Data Preprocessing and Visaulisation in Gephi**
    - Once the dataset was collected, it was not in the right format for network analysis and thus various preprocessing steps had to be performed.
    - Various steps were performed using Python to get the data in the right format for analysis.
    - Once data was ready, the tennis dataset was visualised using Gephi, a graph analysis tool.
    
2. **Metrics Calculations as follows:**
    - Avg. Degree & Highest Degree - To analyze which nodes have the highest degrees and what is the average degree of the network.
    - Degree Distribution - To analyze if the network follows any degree distribution such as log-normal or power law. This helps in understanding the structure of the network and if the data follows any probability distribution.
    - Average Path Length - To analyze the average of the shortest paths in the network and if the network is a small world network or not.
    - Graph density - To analyze if the number of links in the network is equal to the maximum number of nodes in the network. It describes if the network is strongly interconnected or sparse.

3. **Centrality Analysis**
    - Once initial metrics were calculated, centrality of the graph was analysed using various centrality analysis algorithms to find out which nodes have highest influence over the network.
    - The algorithms which were used were: Betweenness, Closeness & Eigenvector Centralities.

4. **Community Detection**
    - Community Detection Algorithms were applied to the network to find out if communities exist within the network.
    - The algorithms that were used for community detectiona are:
    - Modularity - In order to analyze the communities detected by the modularity density. The communities were detected using the Modularity partitioning tool in Gephi.
    - Louvain Algorithm - The algorithm was again implemented using Python and the results were put to Gephi for visualization.
    - Label Propagation Method - In order to analyze the different communities as figured out by the Label Propagation Algorithm. The algorithm was implemented using Python and once the communities were detected, the results were fed to Gephi to visualize the communities.

5. **Link Prediction**
    - Once earlier analysis was done, link prediction was performed on the dataset so that the analysis could be used to forecast future events.
    - The algorithms that were utilised for Link prediction include Random Forest, Rooted PageRank, and SimRank
   
