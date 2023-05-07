# Football-Predictions

The goal will be to predict the winners of matches in the English Premier League. General ideas so far:
1) One model taking in general statistics (goals scored and conceded, home and away, form, possession)
2) One model taking into account player statistics (how much of a difference does it make to Liverpool's winning chances if Salah is injured?) One potential source here is the fantasy football site, which provides player ratings along with statistics. 
3) How do events in-play dramatically change the probabilities? I.e. a red card, injury, goal conceded. Could take into account the likelihood of a team having those events to begin with. 


To consider:
1) What about players coming from other divisions/foreign leagues? How to take into quantify their value?
2) Likewise, how to take into account teams getting promoted? Based on their statistics in the Championship x a weight?
