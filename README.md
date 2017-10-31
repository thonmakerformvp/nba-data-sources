# nba-data-sources
A aggregation of URLs that contain data about the NBA

Live conference standings:
https://data.nba.net/prod/v1/current/standings_conference.json

Summaries of Games:
http://stats.nba.com/js/data/widgets/boxscore_breakdown_20171029.json
Edit *20171029* to be the date you want summaries for.

Scores of todays games:
https://data.nba.com/data/10s/v2015/json/mobile_teams/nba/2017/scores/00_todays_scores.json

Stats summaries of todays game:
http://stats.nba.com/js/data/widgets/scores_leaders.json

Lead trackers of game:
https://data.nba.net/data/10s/prod/v1/20171030/0021700092_lead_tracker_2.json https://data.nba.net/data/10s/prod/v1/20171030/0021700092_lead_tracker_1.json

For the game lead trackers: Each game has 4 different .json pages, one for each quarter - the quarter each page is for is represented by the number at the end of the url right before the '.json'. Each game's lead data also has the gameid or gid and date in the url.
