# fun_with_pagerank
Using pagerank for a symple NHL team performance analysis model

Inspired by Shael Brown's 2017 article "A pagerank model for player performance assessment in basketball, soccer and hockey", I decided to try to experiment with a similar model to assess team performance using data from the last 5 NHL regular seasons (all data obtained from hockey-reference.com).

The model creates links between two teams with weights based on the results and scores off all games they have played over this period, with more recent seasons weighted more heavily, leading to satisfactory results.