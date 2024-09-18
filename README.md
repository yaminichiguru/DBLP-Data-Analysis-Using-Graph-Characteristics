# DBLP-Data-Analysis-Using-Graph-Characteristics

## Overview

This project, completed as part of the DASC 5300/CSE 5300 Foundations of Computing course, involves analyzing a DBLP dataset using graph theory to extract meaningful insights. The DBLP dataset includes publications, authors, conferences, and citations from the field of computer science. Our goal is to explore the relationships between these entities by modeling the data as graphs and performing various analyses on the resulting graph structures.

## Project Objectives

The main objectives of this project are:
1. **Data Preprocessing:** Extract and preprocess data from the provided DBLP dataset to create a graph structure.
2. **Graph Construction:** Build three types of graphs:
   - An **Author Collaboration Graph** where nodes represent authors and edges represent co-authorship.
   - A **Paper Citation Graph** where nodes represent papers and directed edges represent citations between papers.
   - An **Author-Venue Graph** connecting authors to the conferences or journals where they published.
3. **Graph Analysis:**
   - Compute and analyze key graph characteristics.
   - Find maximal groups of authors who are mutually connected (i.e., cliques).
   - Identify the top 5 to 10 most-cited papers or the authors with the most publications.

## Data Set

The DBLP dataset used in this project contains bibliographic information on computer science publications and was provided in `.json` format. The dataset includes authors, publications, citation relationships, and conference venues.

## Graph Analysis

The analysis performed on the constructed graphs includes:
- **Graph Characteristics:** Basic graph metrics like degree distribution, clustering coefficients, and path lengths to understand the network structure.
- **Mutual Author Groups:** Detection of maximal cliques where authors have co-authored papers with each other.
- **Top Publications/Authors:** Identification of the most cited papers and/or the most prolific authors in the dataset.

## Tools and Technologies

The project is implemented in **Python**, and the following tools/libraries were used:
- **NetworkX**: For graph creation and analysis.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib**: For visualization of graphs and analysis results.
- **Jupyter Notebook**: For running code and visualizing outputs.

## Results and Analysis

For a detailed report on the analysis performed, including graph metrics, top authors/papers, and other insights, refer to the `report/` directory. Key findings from the project include:
- Maximal cliques of authors who have co-authored multiple papers.
- The most cited papers from the dataset.
- Authors with the most publications across various conferences and journals.

## Acknowledgments

This project was completed as part of the Foundations of Computing course under the guidance of Professor Sharma Chakravarthy at the University of Texas at Arlington.

