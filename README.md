# Topic-Modeling the National Conversation

## Background
Final project for course *Unsupervised Algorithms in Machine Learning* (DTSA-5510) at University of Colorado Boulder.

## Description
The project analyzes HuffPost articles labeled as “Queer Voices” to identify dominant topics before and after the 2016 U.S. elections. Using unsupervised machine learning techniques, it uncovers shifts in discourse within the LGBTQ+ community.

## Objective
To provide insights into how the national conversation on LGBTQ+ issues, as reflected in media, evolved during a significant political event.


## Data source
The data can be accessed from [Huggingface](https://huggingface.co/datasets/khalidalt/HuffPost).

## Key Features:
* **Data Collection**: Compilation of headlines and short description of articles from HuffPost.
* **Text Preprocessing**: Cleaning and preparing textual data for analysis, including tokenization, stop-word removal, and lemmatization.
* **Topic Modeling**: Application of Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF) to extract prevalent topics and their evolution over time.
* **Visualization**: Graphical representation of topic distributions to facilitate interpretation of the findings.

## Results (summary)
The table below shows the topics in the Queer-Voices articles before and after the 2016 U.S. elections, lined up so that topics that appeared both before and after are on the same line and highlighted in green. (Note that whether two topics should be considered the same topic involves a judgement call.) Topics within a time period that seem very similar to each other are placed in the same cell, indicating that they should be merged. 

The two new topics in the "after" set that seems most interesting are highlighted in yellow.

![image](https://github.com/user-attachments/assets/ae93213c-5a28-47a4-aea7-2904a671d2e8)

## Conclusion
This analysis highlights how significant political events can influence media focus within the LGBTQ+ community, reflecting broader societal shifts and concerns. Two important "Queer Voices" topics that appeared after the 2016 U.S. presidential election are "donald trump - president - transgender ban" and "anti lgbt - anti gay - law - bill - state."
