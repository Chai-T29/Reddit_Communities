# Clustering Subreddit Communities

Welcome to this notebook on “Clustering Subreddit Communities”! If you’re curious about how we can use machine learning techniques like Spectral Clustering to understand user behavior on Reddit, you’re in the right place. Whether you’re just starting out in ML or looking to explore something new, this project will walk you through the process of uncovering hidden community structures based on user interactions on various Subreddits.

## Project Overview

The main goal here is to apply Spectral Clustering using the Graph Laplacian to understand how users interact across different Subreddits. By analyzing these interactions, we aim to identify communities of related subreddits that users tend to frequent together. These communities could then be used to develop recommendation systems or other models that predict user behavior.

The results we’ve obtained are pretty exciting, and in the final section, we’ll dive into the implications of these results, what they tell us about user behavior, and where there might be room for improvement.

## Why This Matters

Reddit is a vast platform with countless communities, and understanding how these communities connect can provide valuable insights. For instance, knowing which Subreddits are often visited by the same users can help in creating better content recommendations, improving user engagement, or even in moderating content more effectively.

## What’s Inside

Here’s a quick look at what you’ll find in this notebook:

1. Importing Libraries and Data:
  - We start by loading the necessary libraries and our dataset, which contains user interactions on Reddit.
2. Preprocessing the Data:
  - Before diving into the analysis, we clean and preprocess the data to ensure that each user’s interactions are standardized. This way, no single user can disproportionately influence the results.
3. Constructing Matrices:
  - With the data ready, we construct the Adjacency, Degree, and Graph Laplacian matrices. These matrices form the foundation for our Spectral Clustering algorithm.
4. Implementing the Algorithm:
  - We implement the Spectral Clustering algorithm, which involves calculating eigenvalues and eigenvectors of the Graph Laplacian. This is a crucial step in identifying the natural clusters within the data.
5. K-Means Clustering:
  - After computing the eigenvectors, we apply the K-Means algorithm to group the Subreddits into clusters. Each cluster represents a community of Subreddits that users frequently visit together.
6. Results and Observations:
  - Finally, we visualize and analyze the clusters we’ve identified. You’ll see how related Subreddits form communities and what these communities might tell us about user behavior.

## Wrapping Up

The insights from this project could be a stepping stone for building recommendation systems or even improving user experience on Reddit. However, it’s important to keep in mind that this is just one approach, and there may be other, perhaps simpler, methods that could yield similar or even better results.

We hope you enjoy working through this notebook and find it both informative and engaging. If you’re new to ML, don’t worry—take your time, and feel free to experiment with the code. Happy learning!

## References

1. Jianbo Shi and J. Malik, “Normalized cuts and image segmentation,” in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 22, no. 8, pp. 888-905, Aug. 2000, doi: 10.1109/34.868688.
2. Yao Xie, “Spectral Clustering.” Class lecture, Computational Data Analytics, Georgia Institute of Technology, Atlanta, GA. August 21, 2024.

Feel free to dive in and start exploring!
