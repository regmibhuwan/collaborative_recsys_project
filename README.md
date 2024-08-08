# Collaborative Recommender System Project

This project implements a collaborative filtering recommender system as part of the Machine Learning Specialization by Andrew Ng on Coursera. The goal is to build a recommender system that provides personalized movie recommendations based on user ratings.

## Description

The repository contains the implementation of a collaborative filtering recommender system using matrix factorization techniques. The main components of the project include:
- Data preprocessing and normalization.
- Collaborative filtering with gradient descent optimization.
- Evaluation of the recommender system's performance.

## Repository Structure

- **data/**: Contains the dataset files used for building the recommender system.
- **images/**: Contains 11 images related to the project.
- **C3_W2_Collaborative_RecSys_Assignment.ipynb**: Jupyter notebook with the main implementation of the collaborative filtering recommender system.
- **public_tests.py**: Python script with public tests for the implementation.
- **recsys_utils.py**: Utility functions used in the recommender system implementation.
- **small_movie_list.csv**, **small_movies_b.csv**, **small_movies_R.csv**, **small_movies_W.csv**, **small_movies_X.csv**, **small_movies_Y.csv**: Small movie dataset files.

## Getting Started

### Prerequisites

To run this project, you need the following dependencies:
- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/collaborative_recsys_project.git
   cd collaborative_recsys_project
   
2. Install the required dependencies:

pip install -r requirements.txt

3. Open the Jupyter notebook and run the cells:

jupyter notebook C3_W2_Collaborative_RecSys_Assignment.ipynb


## Usage
Run the Jupyter notebook to build and evaluate the collaborative filtering recommender system. The notebook includes detailed explanations and code cells that guide you through the implementation process.

## Results
The recommender system successfully generates personalized movie recommendations based on user ratings. The performance of the system is evaluated using metrics such as mean squared error (MSE).
