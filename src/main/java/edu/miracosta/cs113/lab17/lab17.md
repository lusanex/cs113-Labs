## Prim's Minumum Spanning Tree(MST)

Visited Vertices\
0,1,7,6,5,2,8,3,4  

0,1,2,3,4,5,6,7,8\
0,4,4,7,9,2,1,8,2

|value |0|1 |2| 3|4 |5 |6 |7 |8 |
|------|-|-|-|-|-|-|-|-|-|
|key   |0|INF |INF |INF |INF |INF |INF |INF |INF|


|value |0|1 |2| 3|4 |5 |6 |7 |8 |
|------|-|-|-|-|-|-|-|-|-|
|key   |0|4 |INF |INF |INF |INF |INF |8 |INF|


|value |0|1 |2| 3|4 |5 |6 |7 |8 |
|------|-|-|-|-|-|-|-|-|-|
|key   |0|4 |8|INF |INF |INF |INF |8 |INF|


|value |0|1 |2| 3|4 |5 |6 |7 |8 |
|------|-|-|-|-|-|-|-|-|-|
| key  |0|4 |8|INF |INF |INF |1|8 |7|


|value |0|1 |2| 3|4 |5 |6 |7 |8 |
|------|-|-|-|-|-|-|-|-|-|
|key   |0|4 |8|INF |INF |2|1|8 |6|


|value |0|1 |2| 3|4 |5 |6 |7 |8 |
|------|-|-|-|-|-|-|-|-|-|
|key   |0|4 |4|14|10|2|1|8 |6|


|value |0|1 |2| 3|4 |5 |6 |7 |8 |
|------|-|-|-|-|-|-|-|-|-|
|key   |0|4|4|7|10|2|1|8 |2|


|value |0|1 |2| 3|4 |5 |6 |7 |8 |
|------|-|-|-|-|-|-|-|-|-|
|key   |0|4|4|7|9|2|1|8 |2|


