# WL kernel Data

This repository contains the dataset used in our evaluation, which includes edges from all the
600 benign and attack scenario graphs. 

## Format

Tab-separated file with one edge on each line in the following format:

```
source-id	source-type	destination-id	destination-type	edge-type	graph-id
```

Graph ID's correspond to scenarios as follows:
   
   1. YouTube (graph ID's 0 - 99)
   2. GMail (graph ID's 100 - 199)
   3. VGame (graph ID's 200 - 299)
   4. Drive-by-download attack (graph ID's 300 - 399)
   5. Download (graph ID's 400 - 499)
   6. CNN (graph ID's 500 - 599)

## Construction

The dataset is almost the same as the one of streamspot[sbustreamspot-data][1], except that a line of markup representing the end of the scene.


[1]: https://github.com/sbustreamspot/sbustreamspot-data
