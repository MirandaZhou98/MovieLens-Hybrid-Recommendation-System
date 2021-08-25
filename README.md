# MovieLens-Hybrid-Recommendation-System
Hybrid recommendation system for providing movie recommendations to users

## Objective
Our objective is to build a production-quality movie recommendation pipeline which provides a personalizied TOP-10 list of movies specific to each users. The goal of this new pipeline is to increase user retention for the platform and provide a better experience.

## Method
1) Data analysis to understand how to approach our problem.
2) 2 Baseline models as sanity checks: 1. always recommend most popular movies 2. predict rating by average of user's ratings and movie's ratings
3) Hybrid Recommendation System where we divide users into 3 categories: new (content based), moderate (matrix factorization), and avid (wide & deep learning) and use different models for each.
