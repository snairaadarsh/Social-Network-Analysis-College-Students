# Social Network Analysis of College Student Interactions (2025)

This repository presents a Social Network Analysis (SNA) study conducted on survey data collected from college students to analyze patterns of interaction, influence, and community formation. The project applies graph-based analysis techniques to uncover structural properties of student social networks and identify key individuals and communities within the network.


Project Overview
----------------
Social Network Analysis provides powerful tools to study relationships and interactions between individuals. In this project, student survey data is modeled as a graph where nodes represent students and edges represent interactions or relationships between them.

The analysis focuses on understanding:
- Influence and importance of individuals in the network
- Community structures and group formations
- Overall connectivity and interaction patterns among students


Dataset
-------
The dataset consists of survey responses collected from college students, capturing interaction or relationship information used to construct the social network graph.

Note: The dataset is anonymized and used strictly for academic analysis.


Methodology
-----------
The project follows these main steps:

1. Data preprocessing and graph construction
2. Creation of an undirected social network using NetworkX
3. Computation of centrality measures to identify influential nodes
4. Community detection to uncover group structures
5. Visualization of the network and analytical results


Network Analysis Techniques
---------------------------
The following Social Network Analysis techniques are applied:

- Degree Centrality: Identifies highly connected students
- Betweenness Centrality: Identifies students acting as bridges between groups
- Closeness Centrality: Measures how quickly information can spread from a node
- Community Detection: Identifies clusters of closely connected students

These metrics help reveal influential individuals and hidden structures within the student network.


Visualization
-------------
Network visualizations and analytical plots are generated using Matplotlib and Seaborn to illustrate:

- Overall network structure
- Centrality distributions
- Community clusters
- Influence patterns among students


Tools and Technologies
----------------------
- Programming Language: Python
- Network Analysis: NetworkX
- Visualization: Matplotlib, Seaborn
- Data Handling: NumPy, Pandas
- Environment: Jupyter Notebook


Project Files
-------------
- centrality.ipynb
  Computes centrality metrics and analyzes influential nodes

- Visualizations_and_inference.ipynb
  Generates network visualizations and interprets analytical results


Key Outcomes
------------
- Identification of influential students using centrality measures
- Detection of community structures within the student network
- Clear visual representation of social interactions and group dynamics
- Insights into how information or influence may flow within the college environment


Applications
------------
- Understanding student collaboration and peer influence
- Improving communication strategies in academic environments
- Identifying key connectors for information dissemination
- Supporting data-driven decision-making in educational institutions


Status
------
Completed

----
This project is intended for academic and educational purposes only. All analyses are performed on anonymized data.
