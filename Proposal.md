# Steam store database
# Intro
This data provides information about games on steam store, such as number of owners and the average playtime etc.
This data was gathered until around May 2019 it's includ most games on the store prior to that date,
this data was provide by Nik Davis on Kaggle:
- data link: https://www.kaggle.com/nikdavis/steam-store-games
# Features of dataset:
- appid: unique identifier for each title
- name: title of the game
- release-date: release date of the game
- english: does the game support english
- developer: name (or names) of developer
- publisher: name (or names) of publisher(s)
- platforms: where does the game published
- required_age: minimum required age according to PEGI UK
- categories: game categories
- genres: game genres
- steamspy_tags: list of top steamspy game tags
- achievements: Number of in-games achievements, if any
- positive_ratings: number of positive ratings
- negative_ratings: number of negative ratings
- average_playtime: average user playtime
- median_playtime: median user playtime
- owners: estimated number of owners. Contains lower and upper bound (like 20000-50000)
- price: current full price of title in GBP
# Data Rows and Columns:
- this data has over 27000 rows and 18 columns.
# Tools:
- Jupyter notebook
- Libraries(Pandas,Numpy,matplotlib)
# Questions
1. What is the most categorie games that has high average playtime.
2. Does the name of the studio developer effict people to buy the game.
3. Does the name of the game has strong effict for making people to buy the game and play for long hours.
4. Does negative ratings and positive ratings has strong effict more than studio developer. 
5. What is the most supported platforms.
