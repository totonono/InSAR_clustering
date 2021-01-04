# InSAR_clustering
Clustering algorithm use for analysing InSAR point cloud

Code for:
Machine Learning Methods for Identification of Local and Global Trends in InSAR datasets 
Vancouver Island University - Masters of GIS Applications
Written in Python3

This code supplements a masters thesis which researches and analyzes existing machine learning algorithms to assess their applicability in identifying local and regional trends within InSAR datasets. The focus is on unsupervised clustering algorithms, which are best suited for identifying patterns within a single dataset. Nine clustering algorithms are investigated and tested on artificial datasets created for this research; prior to testing using a real InSAR dataset. To begin, one attribute is clustered at a time. The aim of this initial step is to assess the significance of the statistical outputs and the ability to replicate current manual techniques for each algorithm. From the single attribute testing using each of the nine machine learning models identified from the literature review, the research advances to multiple attribute testing using a selection of four of the top performing machine learning algorithms. The evolution of incorporating multiple attributes into one clustering output aims to advance data analysis techniques beyond their current capacity. A standalone Python script with a GIS compatible output is used to present the findings and to facilitate the use of the technique for other point cloud datasets. The overarching theme of this research encompasses deeper value extraction, efficiency, standardization, and replicability.

LEGEND
AD6 represents single attribute analysis with an artificial InSAR dataset, the data is included as a csv file for testing.
MA_PERMIAN uses multiple InSAR attributes within clustering algorithms
The SCRIPT file is a top to bottom script with AD6 for running pre-processing, clustering, assessments, and conversions to ArcPro Shapefiles. This is the complete workflow to aid in the assessment of the analysis. 

Please contact for the full thesis document.
