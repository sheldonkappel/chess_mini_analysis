# Chess Games Mini-Analysis in Python

<img src = "chess.jpg" alt = "" width = "378" height = "250">

This is more so a work-in-progress as the majority of the notebook file involves data manipulation and cleaning and not much visualization. I will add onto this later.

## Overview
* Pulled data for June 2016 from the Lichess (online chess platform) database and converted the data from [PGN format](https://en.wikipedia.org/wiki/Portable_Game_Notation) to a CSV format with the [pgn2data library](https://pypi.org/project/pgn2data/)
* Cleaned and manipulated the data, removing extraneous columns, handling NaN values, etc.
* Grouped the games into 5 opening categories and looked at the distribution of these opening players with the average ratings of the players in the respective games
* Looked at the effect of time control on the amount of games lost by time forfeit.

## TODO
* Analyze more specific openings and their winrates for White and Black
* See which openings are popular with titled players
* Delve deeper into opening popularity

## Results
