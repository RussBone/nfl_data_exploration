# Analysis of NFL Scores-1999 to Present
Data is from the 1999 NFL season to present. It does not include preseason games, but does include postseason games.

## Columns:

- 'game_id': The ID of the game as assigned by the NFL
- 'season': The year of the NFL season. This reperesents the whole season, so regular season games that happen in January as well as playoff games will occur in the year after this number.
- 'game_type': What type of game? One of the following values:
    - REG: a regular season game
    - WC: a wildcard playoff game
    - DIV: a divisional round playoff game
    - CON: a conference championship
    - SB: a Super Bowl
- 'week': The week of the NFL season the game occurs in. This will be 1-17 for the regular season, 18 for wildcard playoff games, 19 for divisional playoff games, 20 for conference championships and 21 for Super Bowls.
- 'gameday': The date on which the game occurred.
- 'weekday': The day of the week on which the game occcured.
- 'gametime': The kickoff time of the game. This is represented in 24-hour time and the Eastern time zone, regardless of what time zone the game was being played in.
- 'away_team': The away team.
- 'away_score': The number of points the away team scored.
- 'home_team': The home team. Note that this contains the designated home team for games which no team is playing at home such as Super Bowls or NFL International games.
- 'home_score': The number of points the home team scored.
- 'location': Either Home if the home team is playing in their home stadium, or Neutral if the game is being played at a neutral location. This still shows as Home for games between the Giants and Jets even though they share the same home stadium.
- 'result': The number of points the home team scored minus the number of points the visiting team scored. Equals home_score - away_score.
    - If negative, away team was the victor
    - If positive, home team was the victor
    - If 0, the game ended in a tie. (Only regular season)
- 'total': The sum of each team's score in the game. Equals home_score + away_score.
- 'gsis': The id of the game issued by the NFL Game Statistics & Information System.
- 'pfr': The id of the game issued by Pro Football Reference
- 'pff': The id of the game issued by Pro Football Focus
- 'espn': The id of the game issued by ESPN
- 'spread_line': The spread line for the game. A positive number means the home team was favored by that many points, a negative number means the away team was favored by that many points. This lines up with the result column.
- 'total_line': The total line for the game.
- 'roof': What was the status of the stadium's roof? Will be one of the following values:
    - outdoors: An outdoor stadium
    - open: Stadium has a retractable roof which was open
    - closed: Stadium has a retractable roof which was closed
    - dome: An indoor stadium
- 'surface': What type of ground the game was played on
- 'temp': The temperature at the stadium (for outdoors and open only)
- 'wind': The speed of the wind in miles/hour (for outdoors and open only)
- 'away_coach': Name of the head coach of the away team
- 'home_coach': Name of the head coach of the home team
- 'referee': Name of the game's referee (head official)
- 'stadium': Name of the stadium
- 'victor': Name of the team that won the game