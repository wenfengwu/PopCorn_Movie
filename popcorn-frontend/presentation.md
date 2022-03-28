# Summary
* A movie website allow users to browse, search, rating and post comments on movies.
* Offer unique recommendations to the users according to their favor.

# Framework
* React library to display frontend html pages to empower frontend user interface
* Java spring boot to build backend APIs and use JSON to interact with frontend
* MongoDB to realize flexible many to many relationships
* Python to extract, transfer and load data to database and training machine learning model.

# Features
* Frontend: Single page application
** Display most popular movies by using carousel and complement auto play function
** Custom rating bar and like button
** Use modal to render pop up window
** Long comments expandable with click to read more
** One button click to shuffle with different recommendations

* Backend: Java Springboot
** Java spring session configuration to store user session in the db. So even user close the site, session can be persisted for longer period of time.
** Java Auth configuration to keep the website secure. Limit access and api call to unauthorized user.

  he can still keep his wishlist and watchlist

** better understand spring beans and autowiring  to connect backend and frontend through RESTful API
** spring mongodb queries to do CRUD and send JSON to frontend to display

# Recommendation system similar to spotify
Use K-nearest neighbors algorithms to build a recommendation system.Including feature extraction from raw data, and train a model using annoy.
Pick the most popular formula (angular) to find the nearest distance.

Integrate with backend api call to perform online inference

