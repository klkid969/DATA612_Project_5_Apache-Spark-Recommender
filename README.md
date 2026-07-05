# DATA612 - Project 5: Apache Spark Recommender System

## Overview

This project demonstrates how an Item-Based Collaborative Filtering recommender system can be adapted from a traditional Python implementation to Apache Spark.

Rather than developing a new recommendation algorithm, the focus of this project is to compare how the same recommendation logic can be implemented using a distributed computing framework.

## Objectives

- Create and configure an Apache Spark environment.
- Build a movie ratings dataset using Spark DataFrames.
- Transform the data into a user-item matrix.
- Compute item-to-item similarity using cosine similarity.
- Generate personalized movie recommendations.
- Compare the Spark implementation with the original Python/Pandas implementation.
- Discuss scalability, implementation tradeoffs, and real-world applications.

## Technologies Used

- Python
- Apache Spark (PySpark)
- Pandas
- NumPy
- Scikit-learn
- Google Colab

## Files Included

- `DATA612_Project_5_Apache_Spark_Recommender.ipynb`
- `DATA612_Project_5_Apache_Spark_Recommender.pdf`

## Key Takeaways

This project demonstrates that while a traditional Pandas implementation is well suited for small datasets, Apache Spark provides a scalable framework capable of processing much larger datasets by distributing computations across multiple machines. The project highlights the tradeoff between simplicity and scalability while reinforcing the principles of collaborative filtering.

---

**Course:** DATA 612 - Recommender Systems

**Author:** Kevin Martin
