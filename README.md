# Active Learning: An Introductory Project

## Overview

This project serves as an introduction to active learning, a machine learning paradigm where the model interactively queries the user (or another source) to obtain the most useful data points for training. The focus is on exploring the basic concepts, methodologies, and potential applications of active learning through an accessible and practical implementation.

## Key Features

1. Implements a simple active learning pipeline.
2. Demonstrates common query strategies like uncertainty sampling and random sampling.
3. Uses a real-world dataset to simulate a practical active learning workflow.
4. Includes detailed documentation and code comments for easy understanding.

## Project Objectives

1. To provide a hands-on introduction to active learning concepts.
2. To compare the performance of active learning with traditional passive learning.
3. To understand how query strategies influence the selection of training data.

## Dataset

The project uses MNIST, and IRIS datasets. The dataset is chosen to ensure simplicity and clarity while illustrating the key concepts of active learning.

## Getting Started

### Prerequisites
Python 3.8 or later
### Required libraries:
`pip install numpy pandas scikit-learn matplotlib`
### Run 
In the folders are two `ipynb` notebooks. 

## Details
- **Uncertainty Sampling**: The model queries the data points it is least confident about.
- **Random Sampling**: Randomly selects data points for querying, used as a baseline.
Results

This project compares the performance of active learning with normal supervised learning, detailing the trade-offs & advantages.

## Future Work

1. Experiment with more advanced query strategies like diversity sampling or query-by-committee.
2. Extend the project to work with deep learning models.
3. Explore applications in domains like medical diagnosis or text classification.
Contributing

Acknowledgments
- Shashwat Gupta, IITK '24 - Project Mentor
- GDG IITK

