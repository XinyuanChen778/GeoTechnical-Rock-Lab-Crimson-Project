# **GeoTechnical-Rock-Lab-Crimson-Project**

Crimson Project – University of Utah MSBA

2024–2025

## **1. Project Overview**

This project supports a geotechnical laboratory by developing a clustering model to group rock samples based on chemical composition. The purpose is to improve sample classification efficiency and provide consistent structure for downstream geological decision-making.

The final approach uses **agglomerative hierarchical clustering with Gower distance**, selected for its ability to handle mixed data types common in rock sample attributes.

## **2. Methods**

- Data cleaning and preparation of chemical oxide variables
- Gower distance to measure similarity between samples
- Agglomerative hierarchical clustering (bottom-up merging procedure)
- Evaluation of cluster options using silhouette scores
- Selection of **6 clusters** based on highest score and interpretability
- Decision tree modeling to extract rules for cluster assignment
- Rule-based classification system for scoring new, unseen samples

## **3. Key Findings**

- The 6-cluster solution provided the best balance between cluster quality and business interpretability.
- Silhouette analysis confirmed clear separation between clusters.
- Decision tree rules enabled transparent classification and reduced manual interpretation time.
- Samples with similar oxide compositions grouped naturally, aligning with geological expectations.

## **4. Skills Demonstrated**

- Unsupervised learning and clustering evaluation
- Application of distance metrics for mixed data
- Decision tree rule extraction
- Interpretation and communication of analytical results
- Collaboration with domain experts in a technical environment
