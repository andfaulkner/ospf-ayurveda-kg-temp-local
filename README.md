# About this project
## Objective
The purpose of this project was to build a knowledge graph integrating pathways from Ayurveda and Western medicine relevant to the treatment of Oral Mucositis or Stomatitis (OM). It was created by Smiti Mittal under the mentorship of Dr. Nibedita Rath to aide the Open Source Pharma Foundation (OSPF)'s ongoing efforts to repurpose Ayurvedic formulations. The graph provides insights into possible mechanisms of action for existing use-cases of the included Ayurvedic formulations and can be used to generate novel hypotheses. We hope this project adds to the relatively new field of literature understanding Ayurvedic medicine through a data-driven, scientific lens.
## Repository Overview 
This repository contains four parts. The 'data_processing' folder contains Python code to scrape and format input data to be suitable for loading into Neo4j Desktop. The 'data_files' folder contains scraped and processed data that can be directly imported into Neo4j Desktop. The 'knowledge_graph' folder contains Cypher scripts to load this data into a graph in Neo4j Desktop. The 'analysis' folder contains Cypher scripts to analyze the resulting graph and pull out the most significant hypotheses. 