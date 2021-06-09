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
For each game, there are several numerical and categorical features available, which are described
below. Not all of them will be useful for the purposes of this contest. Additionally, for anyone
interested in Natural Language Processing, each game includes a text description which likely
contains additional useful data. The vast majority of games also have an associated thumbnail image
which may allow for some Computer Vision experimentation.
The training data consists of games entered in LD38 through 45, while the test data comes from
LD46. LD46 was the largest Ludum Dare competition yet by a substantial margin, presumably due
to a large influx of new participants on account of COVID-19 quarantine; as such, keep in mind that
there may be some shift in the distribution between the training and test sets.


## How to Run Project
For running this project you need to run the ```final_model.ipynb file```. In the end it will output the predictions for testing in a new csv file.

## Libraries you will need
You will need to install following libraries to run the project:
* numpy
* pandas
* keras
* scikit learn
