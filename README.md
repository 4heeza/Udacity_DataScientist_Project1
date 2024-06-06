# "Teamwork makes the dream work" - is that true for board games?
A quick, data-based review on the prevalence of co-operative board games using BoardGameGeek data from 2024

### Project Motivation

Everybody has an experience of a board game getting too acrimonious or taking too long after it becomes simple to identify who is going to win.

Cooperative games typically sidestep these challenges. This project aims to analyse:
1: whether cooperative games are popular with modern audiences;
2: whether games with co-operative mechanics are more prevalent now than they used to be. Reviewing games published since the Baby Boomer generation began in 1946 to today, and;
3: understand whether there is greater demand for co-operative games nowadays vs the norm.

This will all build a picture that indicates to the reader whether cooperative games are worth considering for their future purchases / and are generally received well by BoardGameGeek members.

### Installations 
pandas
numpy
matplotlib
re (Regex)

### File Descriptions
details.csv - A larger file that communicates the attributes of board games (number of players, playtime length, board game categorisation & mechanics), information on the publisher & key contributors to the development of each game and data on those who own, want, wish & intend to trade the game.
ratings.csv - File with basic information on board games (unique identifiers, name, year published etc.) as well as user ratings and the volume of user ratings of each game

Both from BoardGameGeek and collated by Joakim Arvidsson before sharing on Kaggle.

### How to interact with this project

Project intended to be standalone analysis into this specific topic.

List of key results:
1) Found 5 individual mechanics in the varied lists per game that relate to any form of cooperation: Cooperative Game, Team-Based Game, Alliances, Semi-Cooperative Game & Negotiation.
2) Found 1,590 board games were NaN in the boardgamemechanics column of the details.csv. Elected to exclude these games without listed mechanics from calculations in the analysis as:
  - The mechanics don't relate to individuals or any kind of performance measure that can be imputed - they're adjectives & descriptors based on games where we can't robustly anticipate their characteristics.
  - The proposed analysis is focusing on the prevalence of these kinds of games across on entire dataset - rather than out of smaller subsections.
3) Cooperative games make up 13% of the dataset. They however make up 30% of the top 100 games, 26.8% of the top 250 games, 25.8% of the top 500 games and 24.3% of the top 1000 games (based on rating from BoardGameGeek members).
4) Matching the current perceived popularity poised by 3), cooperative games made up a greater proportion of all games published in the last decade (2016-2025) vs all previous decades reviewed. The difference is very significant.
5) The vast majority of board games are only on small number of member's Trade, Want & Wish Lists on the BoardGameGeek website. The range is very large though, with a small number of board games being on lists 1000s or 10000s of times.
6) Using median averages rather than mean averages to assess the prevalence of co-operative games on Trade / Want / Wish lists seemed like a more sensible approach and a better way to account for the range & outliers.
7) Cooperative games generally appear on Trade / Want / Wish lists more than non-cooperative games and vs the medians presented when looking at the entire dataset.
8) Cooperative games are wanted and wished for significantly more than other games. And the gap between the lists where BoardGameGeek members want them vs the trade list where they want to dispense of it is also larger - arguably indicating that demand for cooperative games is higher than other games.


### Licensing, Authors & Acknowledgments

Joakim Arvidsson - joebeachcapital - Kaggle GrandMaster
https://www.kaggle.com/datasets/joebeachcapital/board-games#

Board Game Geek
https://boardgamegeek.com/

Christopher Paul High - Meeple Image
https://unsplash.com/photos/yellow-red-and-blue-lego-blocks-fwRMK19zavc
