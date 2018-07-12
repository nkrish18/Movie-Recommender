# Movie Recommender

## Objective

Many applications like netflix use sophisticated algorithms for recommending movies to their users. This project is an attempt of mine to find similar movies for users based on their past behavior and history, and recommend it to them.

## Dataset:

The public MovieLens dataset is used here. It contains real time ratings for several thousand movies.

## Ideology

An item based collaborative filtering technique is used here. The concept is to base recommendations on items as opposed to basing them on the users themselves, the items here being the movies. This is beneficial because an item will always remain the same irrespective of time whereas a person may have different phases at different times. So relationships tend to be more permanent and more direct comparisons can be made. It is also computationally less expensive as items typically have lesser features when compared to people.