# 🕸️ GNN Social Recommender & Network Analysis

## 📌 Project Overview
This project focuses on social network analysis and the implementation of a recommendation system using Graph Neural Networks (GNNs). Specifically, a Graph Convolutional Network (GCN) was developed and trained on the SNAP "Facebook Combined" dataset to learn vector representations (embeddings) of users. The methodology relies on link prediction via supervised learning, aimed at decoding the structural information and latent topologies of the graph.

## 🚀 Key Features
*   **Link Prediction & Recommendations:** Employs supervised learning with negative sampling to train the model, ultimately generating personalized friend recommendations based on Cosine Similarity.
*   **Community Detection:** Utilizes the K-Means algorithm on the generated embeddings to successfully identify 10 distinct user communities (clusters).
*   **Influencer Identification:** Analyzes Degree Centrality to detect network "Super-Connectors" (e.g., a central hub user with 1,045 connections) who are critical for information flow.
*   **Dimensionality Reduction & Visualization:** Uses t-SNE to project the 16-dimensional learned embeddings into a 2D space, visualizing the clear separation of communities and high-influence nodes using Matplotlib[.

## 🛠️ Tech Stack
*   **Deep Learning:** PyTorch Geometric
*   **Machine Learning & Analytics:** scikit-learn (K-Means, t-SNE)
*   **Visualization:** Matplotlib
