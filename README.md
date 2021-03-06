# LA_Clustering_Dissertation
Applied Data Science BSc Dissertation Project - Clustering Local Authorities using administrative data

# Clustering UK Local Authorities using variables derived from administrative data sources

Cluster analysis via machine learning provides the opportunity for computer algorithms to discover patterns within data that were previously undetected by human analysis. This project uses several clustering algorithms in order to group UK Local Authorities together into clusters, which can then be used by the Office for National Statistics in their yearly population estimates. 

The Office for National Statistics currently creates Local Authority groupings by geographical closeness of authorities, but this risks under or over-estimating certain key demographics in the UK's national population. Grouping LA's instead based on commonalities found in administrative data will allow for more accurate population estimates to be generated.

Data derived from administrative sources was used in assessing 4 different clustering algorithms. The data was standardised across each algorithm, with dimensionality reduction applied via Principal Component Analysis. The validity of these clusters was then assessed using the silhouette score metric, as well as via manual evaluation from subject experts at the ONS. Results from these two evaluation methods were then compared in order to find the most successful techniques. 

Both K-means and Self Organising Map algorithms achieved similar silhouette scores, with Hierarchical clustering receiving lower scores and the Tensorflow K-means estimator proving to be too computationally expensive. The results of the project show that while each algorithm achieved similar groupings of Local Authorities, these groupings scored relatively low silhouette scores. Manual evaluation was similarly unsuccessful, with the subject experts being unable to identify any clear patterns in the clusters. When compared to current LA classification groups used by the ONS the generated clusters did not appear to correlate to any particular classifications. Despite this the project does provide some valuable insight in how the data influences the algorithms. Recommendations for future work include using data with higher dimensionality and a wider array of origin data sources, as well as investigating additional clustering algorithms. 

Files include IPython Notebook containing all code, PDF report essay, and Word doc containing link to presentation
