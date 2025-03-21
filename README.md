<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title align="center">Exploring Movie Recommendation Systems</title>
</head>
<body>
    <div align="center">
        <img src="assets/icon.png" alt="Icon Image" width="200">
        <h1>Exploring Movie Recommendation Systems</h1>
        <h3>Singapore Institute of Technology</h3>
        <h4>March 21, 2025</h4>
    </div>

</body>
</html>


## Models and Dataset

This project leverages two recommendation models to explore movie suggestion systems. The **Item-Item Collaborative Filtering Model** uses a similarity-based approach, calculating movie similarities based on user interactions to recommend items akin to those a user has previously rated highly. 

The **Hybrid Recommendation Model** combines collaborative filtering with content-based techniques, integrating user ratings and movie metadata for a more robust and personalized recommendation system. Both models are implemented and evaluated using Python in Jupyter notebooks.

The dataset used is **The Movies Dataset** from Kaggle ([link](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?resource=download&select=keywords.csv)), a comprehensive collection of movie-related data. It includes files such as `movies_metadata.csv` (movie details like title, genres, and release date), `ratings.csv` (user-movie ratings), and `keywords.csv` (movie keywords). This rich dataset enables exploratory data analysis, feature engineering, and model training, providing insights into user preferences and movie characteristics.

## Abstract

Recommendation systems are pivotal in enhancing user experience by providing personalized content suggestions. This project explores movie recommendation systems through the development and evaluation of two distinct approaches: an item-item collaborative filtering model and a hybrid recommendation model. Additionally, comprehensive exploratory data analysis (EDA) and feature engineering are conducted to uncover insights and optimize model performance.

## Introduction


### Prerequisites

To replicate this project, ensure the following prerequisites are met:

- **Python Version:** 3.8 or higher
- **Dependencies:** Install required packages by running:

```
pip install -r requirements.txt
```

- **Hardware Requirements:** Standard CPU; GPU optional for faster computation.
- **Dataset:** Movie-related dataset (e.g., The Movies Dataset from Kaggle), which is preprocessed in the notebooks.


### Project Structure

#### Data Analysis and Preparation

`EDA.ipynb` employs visualizations (e.g., histograms, heatmaps) and statistical methods to explore the dataset. Missing values are handled, and features like movie genres or user demographics are engineered for downstream use.

#### Item-Item Model

`final(2).ipynb` focuses on collaborative filtering by constructing an item similarity matrix. The model leverages user-movie interaction data to generate recommendations, optimized for scalability and accuracy.

#### Hybrid Model

`class_benchmark.ipynb` integrates collaborative and content-based techniques, potentially using ensemble methods or deep learning. Hyperparameter tuning and cross-validation ensure optimal performance.

## Results

_**A more indepth analysis is covered inside the respective ipynb._

## Conclusion

This project showcases the design and implementation of movie recommendation systems, highlighting the strengths of item-item and hybrid methodologies. Through rigorous analysis and experimentation, we provide a foundation for further advancements in personalized content delivery.

## References:


Banik, R. (2021). The movies dataset. Kaggle. https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

Ferretti, J. (2021). Exploring the IMDb movies dataset. Kaggle. https://www.kaggle.com/code/jacopoferretti/exploring-the-imdb-movies-dataset/notebook

Omar, E. Y. (2021). Metadata-based recommender system. Kaggle. https://www.kaggle.com/code/elyousfiomar/metadata-based-recommender-system

Poraiyar, P. (2021). IMDB movies: All types of recommender system. Kaggle. https://www.kaggle.com/code/padmanabhanporaiyar/imdb-movies-all-types-of-recommender-system



