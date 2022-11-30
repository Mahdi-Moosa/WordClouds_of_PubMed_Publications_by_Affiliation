# WordClouds_of_PubMed_Publications_by_Affiliation

Draws word cloud from PubMed data of fetched publcations (based on Affiliation).

Jupyter notebook shows example word clouds of MeSH terms and publication abstracts. Can be easily modified to plot word clouds from other metadata.

Steps:
* Fetches all PubMed IDs (PMIDs) of the query Affiliation.
* Fetches metadata of all PMIDs from the previous step.
* Performs necessary cleanings of the text data to be plotted.
* Plots text data as word clouds.
