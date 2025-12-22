---
layout: single
title: Projects
author_profile: true
sidebar:
  nav: "projects"
---

This page highlights a selection of my data science projects, showcasing applied analysis on real-world datasets. Each project includes an overview, key insights, outcomes, and the tools used.

# Main Projects

## Causal NLP Knowledge Extraction
*2025*
- **Overview**: Built a pipeline to extract structured and causal relationships from unstructured text.
- **Key Insights**:
  - Stored extracted triples in a Neo4j knowledge graph for querying and downstream analysis.
  - Emphasized precision and constraint-based extraction to avoid unsupported relationships.
- **Outcome**: Enabled structured querying of causal claims across large document collections.
- **Tools**: Python, Neo4j, Docker  
- **Link**: [Causal NLP Knowledge Extraction](https://github.com/jessicabat/causal-nlp-extraction)

## Mouse Circadian Rhythm Analysis
*2025*
- **Overview**: Analyzed minute-level activity and core body temperature data across two weeks.
- **Key Insights**:
  - Studied sex-based differences and estrus-related temporal patterns under controlled light cycles.
  - Focused on time-series analysis and visualization.
- **Outcome**: Revealed consistent temporal patterns that differ by sex and biological cycle.
- **Tools**: Python, pandas, matplotlib, Jupyter

## Spam Email Classification
*2025*
- **Overview**: Developed a robust spam detection system by evaluating various statistical and machine learning models across multiple data transformation techniques.
- **Key Insights**:
  - Preprocessed datasets and optimized model performance with transformations.
  - Tested multiple algorithms and ensemble methods to enhance precision.
  - Used PCA for feature interpretation.
- **Outcome**: Achieved a peak classification accuracy with a Random Forest model on log-transformed data, resulting in a low test error rate of approximately 2.41%.
- **Tools**: R, randomForest, e1071, MASS, knitr
- **Link**: [Spam Email Classification](/assets/files/Spam_Email_Classification.pdf)


## League of Legends Objective Impact Analysis
*2024*
- **Overview**: Conducted large-scale analysis of professional match data to study how early objective control affects win outcomes.
- **Key Insights**:
  - Compared gold, experience, and kill metrics between teams with and without early Rift Herald control.
  - Demonstrated how early-game advantages translate into higher win probability.
- **Outcome**: Quantified the win-rate impact of early objectives to support strategic decision-making.
- **Tools**: Python, pandas, matplotlib, scikit-learn, Jupyter  
- **Link**: [League of Legends Objective Impact Analysis](https://lh-008.github.io/LeagueofLegend-StatAnalysis/)

# Additional Projects

## Predicting Player Salaries in the NBA
*2024*
- **Overview**: Analyzed the performance and demographic factors influencing NBA player market value using data from the 2022-2023 season.
- **Key Insights**:
  - Conducted exploratory data analysis (EDA) to visualize salary distributions and correlations with core basketball metrics.
  - Developed multiple linear regression models to validate the impact of scoring, assists, and rebounding on compensation.
  - Implemented data cleaning and probabilistic imputation techniques for missing value handling.
  - Tested specific hypotheses regarding the relationship between team revenue-driving metrics and individual player salaries.
- **Outcome**: Confirmed that performance metrics such as `Points Per Game`, `Minutes Played`, and `Win Share` are significant determinants of player compensation.
- **Tools**: Python, pandas, Seaborn, Matplotlib, statsmodels

## Image Processing and Classification System
*2024*
- **Overview**: Developed a comprehensive Python-based image processing library and a K-Nearest Neighbors (KNN) classifier for automated image labeling.
- **Key Insights**:
  - Built classes and functions for image manipulation and transformations.
  - Developed image filters and an automated KNN classifier.
- **Outcome**: Produced a modular system capable of both complex visual effects and automated pattern recognition for image datasets.
- **Tools**: Python, NumPy

## NASA Meteorite Landings Exploration
*2023*
- **Overview**: Analyzed a dataset of over 45,000 meteorite landings from NASA’s Open Data Portal to examine global distribution and physical properties.
- **Key Insights**:
  - Performed geospatial analysis to compare the frequency and location of observed "falls" versus recorded "finds."
  - Applied inferential statistics and bootstrapping techniques to calculate confidence intervals for meteorite mass.
  - Conducted a temporal analysis of meteorite recordings by decade to identify historical observation biases.
- **Outcome**: Delivered a comprehensive statistical summary of meteorite impacts, highlighting the relationship between geographic location and recording consistency.
- **Tools**: Python, pandas, SciPy, Matplotlib

## Taylor Swift Music Analysis
*2023*
- **Overview**: Conducted a multi-faceted analysis of Taylor Swift’s discography using Spotify audio features and Genius lyric data.
- **Key Insights**:
  - Built a song recommender system using Euclidean distance metrics to calculate similarity between tracks based on audio qualities.
  - Developed a lyric search engine and keyword extractor using TF-IDF to identify unique thematic elements in each album.
  - Generated visual summaries of musical trends, including valence sentiment analysis and word clouds for specific eras.
- **Outcome**: Provided data-driven insights into the evolution of Swift’s musical style and implemented automated tools for track discovery.
- **Tools**: Python, pandas, Matplotlib, NumPy
