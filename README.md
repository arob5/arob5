# Overview
Welcome to my GitHub! Please see below for descriptions of my personal projects, in addition to links to the relevant repositories containing code and papers. 

# Projects

## [Nearest Positive Definite Matrix C++ Implementation](https://github.com/arob5/nearest-pd-matrix-rcpp.git)
Most recently, I have been writing an implementation of the R *nearPD()* function in C++. Given an "almost" Positive Definite matrix, this function runs an iterative algorithm that converges to the nearest (in the Frobenius Norm) Positive Definite matrix. One use case is finding the nearest correlation matrix when portions of the original "correlation" matrix may have been calculated using slightly different time periods. The convergence of *nearPD()* may be quite slow for large matrices, which motivates this implementation in C++. I will be adding test files quantifying the speed improvements. 

## [Climate Change and Malaria Research Proposal](https://github.com/arob5/climate-change-and-malaria-research-proposal.git)
For an undergraduate senior year elective, I wrote a research proposal for an econometric analysis of the effect of climate change on malaria in Brazil. This proposal was motivated by a literature review of the relevant epidemiologic and economic literature. The data to actually run the proposed analysis exists but is not publicly available. 

## [Document Clustering and Topic Modeling: NNMF compared to SVD and K-Means] (https://github.com/arob5/document-clustering-and-topic-modeling-paper.git)
This analysis evaluates the performance of the Non-Negative Matrix Factorization (NNMF) for two NLP tasks: document clustering and topic modeling. The document clustering and topic modeling results are compared to K-Means and the Singular Value Decomposition (SVD), respectively. The code is written in Scala and included is a paper summarizing the methodology and results.  

## [Conditional Random Field](https://github.com/arob5/conditional-random-field.git)  
I implemented a Linear Chain Conditional Random Field from scratch in Scala. This is a simplified implementation using basic feature functions, not an attempt to compete with the state-of-the-art models currently being used in NLP settings. My CRF implementation is trained on text data and used to label words as nouns, verbs, or adjectives. 

## [Principal Component Analysis used for Image Compression](https://github.com/arob5/PCA-Image-Compression.git)
Here I apply PCA to the well-known Olivetti faces dataset to perform image compression. Accompanying the code is a paper summarizing the methodology and results. 

## [Unsupervised Clustering Analysis on Boston Housing Dataset](https://github.com/arob5/boston-housing-data-clustering-analysis.git)
I perform an unsupervised analysis on the Boston Housing Dataset using PCA and K-Means. This well-known dataset is typically analyzed via supervised methods, so this analysis serves to look more closely at the stucture of the feature space. Accompanying the code is a paper summarizing the methodology and results.

<!--
**arob5/arob5** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
