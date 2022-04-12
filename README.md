# Lichess Data

## Two good reasons to use the API yourself instead of relying on lichess insights: 
1) More specificity (e.g., time control data can be broken down by initial minutes and increment, which is not available in lichess insights)
2) Access any user's data (lichess insights restrict this access).

### Here I break things down and add visualizations through seaborn for openings, time controls, and hour of day and day of week.

This is an example of how to use Lichess API data to find trends within your own games (or someone else's). There's a lot more that can be done, but this may be a useful primer. I'm using a Python wrapper called berserk, which is recommended on the Lichess API page here: https://lichess.org/api.

You can get a token here https://lichess.org/account/oauth/token

Wrapper documentation: https://github.com/rhgrant10/berserk

