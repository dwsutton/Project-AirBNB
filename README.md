# Project_4
In class project repo

Description:
This project laid out the challenge of completing a project in one day in class. We were given a list of Kaggle challenges (listed below) and asked to pick one and work on it until completion or 5 p.m., which ever came first.

My choice:
I weighed several factors when choosing which dataset to undertake. Most importantly which one gave me the most comfort in my ability to assemble a quality product given the time constraint. The Kobe dataset and the Taxi project were considered briefly. However I ruled them out due to dislike of Kobe and the size of the Taxi dataset. I selected the AirBnB challenge, we didn’t need to actually do the challenge. Our goal was to only use the dataset to run through a regression and a random forest problem.

Data:
The dataset accompanying the AirBnB challenge was fairly clean and I was able to quickly move into the EDA phase of the project. 

My approach:
I began by converting two of the columns to date time, for later use (I ended up not using the columns at all). I established a baseline y by normalizing the y column, revealing NDF and US as the top possibilities. NDF was used when survey takers left the destination question blank and when combined with US, amounted to nearly 80 percent of the answers. It is worth noting the other destinations were mostly in western Europe.

I set up X and y, dummying the age, gender and sign-up categories for X and declaring y as the destination column. I proceeded with the logistic regression and scored 58.2 and 58.3 on the training and testing sets. An okay result for the most part but certainly would not win any Kaggle competitions.

I moved on to the random forest classifier, which received scores of 63.3 and 62.8 on training and testing data. Again, an okay score but I wasn’t winning any cash from Kaggle any time soon.

I plotted a confusion matrix and called it a day.

Conclusions:
I felt accomplished having completed this exercise, though without any earth-shattering results or discoveries. Next steps would be creating some visualizations and polishing the Jupyter Notebook since it was going to be used in the presentation phase of this exercise. If given more time I would have liked to try some different models and play around with the parameters a bit, tuning my models.


The assignment was as follows:

Pick a Kaggle competition from the following list. You have the choice of completing a regression problem, a classification problem, or an NLP problem involving either classification or sentiment analysis. Perform some EDA, and fit and evaluate at least two models on the dataset you've chosen.

## Datasets

### Regression
- [Restaurant Revenue Prediction](https://www.kaggle.com/c/restaurant-revenue-prediction)
- [Video Game Sales Prediction](https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings)
- [Box Office Revenue Prediction](https://www.kaggle.com/c/tmdb-box-office-prediction)
- [New York City Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction)

### Classification
- [Predicting a Biological Response](https://www.kaggle.com/c/bioresponse/data)
- [Kobe Bryant Shot Selection](https://www.kaggle.com/c/kobe-bryant-shot-selection)
- [Shelter Animal Outcomes](https://www.kaggle.com/c/shelter-animal-outcomes)
- [Airbnb New User Bookings](https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings)

### NLP
- [Sentiment Analysis on Movie Reviews](https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews) / [Alternative Sentiment Analysis on Movie Reviews](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- [What's Cooking?](https://www.kaggle.com/c/whats-cooking)
- [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started/)
- [Women's E-Commerce Clothing Reviews](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews)

## Timeline
- **10am**: Project introduction.
- **11am**: By 11am, Slack Caroline what dataset you've chosen.
- **5pm**: 5-minute lightning talks where you walk us through your process. **No slides necessary** -- it's fine if you'd prefer walk us through your Jupyter notebook.
- **6pm**: Make sure your project work has been pushed.

## Guidelines

We know this is a short time for a project. We're not expecting anything as polished as project two or three, for example. However, the goal is for you to have something to show for your time. At a minimum, do some EDA and have at least two models fit and scored.
