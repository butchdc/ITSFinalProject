# Traffic Hotspot Detection Using K-Means and GMM Clustering

This repository contains the code and methodologies for detecting traffic congestion hotspots within Auckland, New Zealand, using advanced machine learning techniques—K-Means and Gaussian Mixture Models (GMM). This project is part of the MSE806 Intelligent Transportation Systems course, aimed at contributing to sustainable urban mobility.

## Table of Contents
- [Introduction](#introduction)
- [Project Purpose and Objectives](#project-purpose-and-objectives)
- [Technologies and Techniques](#technologies-and-techniques)
- [Methodology](#methodology)
- [Results and Discussion](#results-and-discussion)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction
Urban traffic congestion is a significant concern affecting economic productivity and quality of life. This project leverages unsupervised learning models—K-Means and GMM—to identify congestion hotspots using Auckland's traffic data. These hotspots can assist in targeted interventions and infrastructure planning.

## Project Purpose and Objectives
**Purpose:** To uncover patterns in Auckland traffic data, enhancing urban planning for efficient transportation.

**Objectives:**
1. **Data Collection and Preprocessing**: Collect and clean traffic data for clustering.
2. **K-Means Clustering Application**: Segment traffic data to identify high congestion zones.
3. **GMM Clustering Application**: Capture complex patterns for comparative analysis with K-Means.
4. **Evaluation**: Assess the effectiveness of each clustering technique.
5. **Visualization**: Develop interactive maps and charts to display hotspots.

## Technologies and Techniques
This project utilizes the following clustering and data visualization tools:
- **Clustering Algorithms**: K-Means and GMM for hotspot identification.
- **Data Visualization**: Power BI for interactive charts and hotspot maps.
- **Data Sources**: Auckland Transport Traffic Count dataset.

## Methodology
### Data Collection
Traffic volume data was collected from Auckland Transport’s traffic count dataset, covering metrics such as traffic flow, GPS coordinates, and peak hour volumes. After cleaning, this dataset was standardized for clustering.

### Data Preprocessing
- **Filtering and Cleaning**: Removed null values and standardized traffic metrics.
- **Feature Engineering**: Created features like “Weekend Traffic ADT” to capture traffic patterns over different time intervals.
- **Outlier Detection**: Used Z-score analysis to improve dataset reliability.

### Clustering Techniques
- **K-Means**: Clustering based on Euclidean distance to segment traffic zones.
- **GMM**: Probabilistic clustering, allowing data points to belong to multiple clusters with certain probabilities.

## Results and Discussion
### Visualization and Interpretation
Interactive maps and scatter plots revealed distinct traffic patterns, helping to identify zones with high congestion. Comparative analysis between K-Means and GMM demonstrated:
- **K-Means**: Simplicity and speed in identifying uniform traffic patterns.
- **GMM**: Flexibility for complex, overlapping clusters with varied congestion patterns.

### Application for Urban Planning
The results offer insights into potential areas for infrastructure improvements, enhancing traffic flow and reducing congestion.

## Conclusion
This project highlights the utility of machine learning techniques in traffic management and urban planning, showcasing how data-driven approaches can address complex urban mobility challenges.
