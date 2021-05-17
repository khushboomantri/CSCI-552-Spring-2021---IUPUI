# CSCI-552-Spring-2021---IUPUI


Handout:  Thursday, March 18, 2021
Due:  11:59 pm, Thursday, April 1, 2021
Total points:  50

In this project,  you will generate a graph visualization for the 2020 National FootballLeague (NFL) regular season games between all 32 NFL teams.  All 17 weeks of the regularseason games can be found at :  http://www.nfl.com/schedules/2020/REG1.

1.  Generate a graph data set with teams as nodes and games between teams as edges.Each node contains the team name, geographic location (city), record in 2020, and thedivision it belongs to.  Each edge contains the score of the game.  If two teams playedtwice with each other, then the scores of both games should be stored in the edge.
2.  Use  D3  to  layout  and  visualize  this  graph.   Each  node’s  initial  location  in  a  graphlayout will be (or near) its geographical location on the US map.  The size of the nodewill reflect it record, and a color can be used to represent it division.  Edges will bedrawn with game scores.

3.  Generate 2 different force-directed layouts of this graph based on two different forcedefinitions.  You need to carefully define the force such that the resulting layout makesense in an intended way. Examples of possible layout criteria include: putting teams inthe same division in a cluster and still maintaining their relative geographic locations;putting  teams  that  are  most  similar  (with  some  similarity  definition)  close  to  eachother, etc.


This Youtube video, https://youtu.be/Mucmb33711A, provides some more details aboutD3 graph layout.  Please submit screenshots of your visualizations,  your D3 source codes,and a description about your force-directed layout methods.
