# Location Recommendation System for Student Accommodations📍

## Overview

A location-based recommendation system that clusters student behavior and preference data to identify optimal student accommodation areas in a city. Leveraging K‑Means clustering (achieved 98% silhouette score), it maps clustered user segments to real-world locations using the Foursquare API, visualized interactively with Folium.

## Features

* **Clustering Methods Evaluated**: Tested K‑Means, DBSCAN, and Hierarchical clustering using silhouette scores; K‑Means was selected as the most effective.
* **User Profiling**: Grouped student habits and accommodation preferences into meaningful clusters.
* **Real-World Mapping**: Integrated with Foursquare API to locate and present real accommodation hotspots on a map.
* **Visualization**: Folium-based interactive visualizations of clusters and recommended areas.
* **Collaborative Workflow**: Team of three executed data preprocessing, labeling, clustering analysis, and performance tuning.

## Tools & Tech Stack

* Python (data processing, clustering, integration)
* Foursquare API (location data, venue mapping)
* Folium (interactive map rendering)

## Usage Instructions

1. Clone this repository.
2. Install dependencies (e.g., `pandas`, `scikit-learn`, `requests`, `folium`).
3. Prepare student preference dataset and preprocess (cleaning, feature engineering, labeling).
4. Run clustering evaluation to confirm silhouette score and cluster parameters.
5. Fetch location data via Foursquare and generate Folium map output.
6. Visualize and review cluster-based accommodation suggestions.

## Results

* Achieved a clustering silhouette score of \~98% using K‑Means.
* Successfully mapped clusters to weighted accommodation hotspots across the target city.
* Interactive Folium map enables intuitive exploration of recommended locations.

## Team & Contribution

* Data preprocessing, labeling, and dataset division done collaboratively by three members.
* Shared responsibility for clustering evaluation, Foursquare integration, and visualization refinement.
 
