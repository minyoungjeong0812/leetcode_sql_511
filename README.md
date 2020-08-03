# leetcode_sql_511

Table: Activity

+--------------+---------+
| Column Name  | Type    |
+--------------+---------+
| player_id    | int     |
| device_id    | int     |
| event_date   | date    |
| games_played | int     |
+--------------+---------+
(player_id, event_date) is the primary key of this table.
This table shows the activity of players of some game.
Each row is a record of a player who logged in and played a number of games (possibly 0) before logging out on some day using some device.
Write an SQL query that reports the first login date for each player.


The query result format is in the following example:


[2020-08-03-032157.png](https://postimg.cc/T5h8zK5V)
