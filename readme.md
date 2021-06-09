## Project Descrption

Ludum Dare is a well-known, long-running online game jam. It is essentially a competition in which
contestants develop a game in 48 or 72 hours, ideally relating to a particular theme, and receive
rankings (1-5 stars) from other contestants. There are two categories: the "compo" (developers work
alone, using no premade assets, and have only 48 hours) and the "jam" (contestants may work in
teams, using some premade assets, and may take up to 72 hours). Games receive an overall rating
as well as ratings for individual categories (fun, theme, innovation, graphics, audio, humour, and
mood).
This data set consists of data about all games entered in the last 9 iterations of the Ludum Dare
competition, obtained via the public API of the official Ludum Dare site. Each entry is labeled
according to its final average score in the "overall" category (from 1 to 5 stars, rounded to the nearest
integer, or 0 if the game did not receive enough ratings to officially rank). This is a classification
problem with 6 (unbalanced) classes.


## How to Run Project
For running this project you need to run the ```final_model.ipynb file```. In the end it will output the predictions for testing in a new csv file.

## Libraries you will need
You will need to install following libraries to run the project:
* numpy
* pandas
* keras
* scikit learn
