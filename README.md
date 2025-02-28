# Analysis of NFL Statistics-2000 to 2023
The NFL has undergone many structural changes this century. It has increased the number of teams with the addition of the Houston Texans in 2002, increased the number of games fom 16-17 in 2021, and has undergone rule change after rule change. Not only are teams constantly changing with player and coach turnover, the landscape of the NFL season is constantly evolving. This leads to the purpose of this project: to determine how the NFL has responded and if there are any general trends in response to the ever evolving game.

- Main Questions
    - How has the NFL changed over time?
    - Are there any interesting outlier seasons?

## Data Source:
- Data collected from each NFL game's boxscore data
- Data is from the 2000 NFL season to the 2023 NFL season
    - Does not include preseason games
    - Includes postseason games
    - Some games happen the year after the season year, but are still considered to be in the earlier season.
        - Most of these games are postseason games

## Attributes:

**`season`**

The Season's Year

**`event_date`**

The Date of the Game

**`name`**

nflSlowPy Name 

**`alias`**

nflSlowPy Alias

**`rush_att`**

Total Offensive Rushing Attempts

**`rush_yds`**

Total Offensive Rushing Yards

**`rush_tds`**

Total Offensive Rushing Touchdowns

**`pass_cmp`**

Total Offensive Passes Completed

**`pass_att`**

Total Offensive Passes Attempted

**`pass_cmp_pct`**

Ratio of Passes Completed to Attempts

**`pass_yds`**

Total Offensive Passing Yards

**`pass_tds`**

Total Offensive Passing Touchdowns

**`pass_int`**

Total Offensive Passing Interceptions

**`passer_rating`**

Team's Total Passer Rating

**`net_pass_yds`**

Total Offensive Passing Net Yards

**`total_yds`**

Overall Offensive Yards

**`times_sacked`**

Total Times That a Quarterback(s) Was Sacked For

**`yds_sacked_for`**

Total Yards That a Quarterback(s) Was Sacked For

**`fumbles`**

Total Fumbles – Includes Those That Were Recovered and Lost

**`fumbles_lost`**

Fumbles Lost and Recovered by Opponent's Defense

**`turnovers`**

Total Turnovers, Including Fumbles Lost and Interceptions

**`penalties`**

Total Number of Offensive and Defensive Penalties

**`penalty_yds`**

Total Number of Offensive and Defensive Penalty Yards

**`first_downs`**

Total Offensive First Downs

**`third_down_conv`**

Offensive Third Down Conversions

**`third_down_att`**

Offensive Third Down Attempts

**`third_down_conv_pct`**

Ratio of Third Down Conversions to Attempts

**`fourth_down_conv`**

Offensive Fourth Down Conversions

**`fourth_down_att`**

Offensive Fourth Down Attempts

**`fourth_down_conv_pct`**

Ratio of Fourth Down Conversions to Attempts

**`time_of_possession`**

Total Offensive Possession Time in Seconds 