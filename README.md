# WL kernel Data

This repository contains the `ALL` dataset, which includes edges from all the
600 benign and attack scenario graphs. The `YDC` and `GFC` datasets can be derived
from `ALL` by picking graph ID's having scenarios as follows:

   * `YDC`: YouTube, Download, CNN
   * `GFC`: GMail, VGame, CNN 

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

The dataset is almost the same as the one of streamspot, except that a line of markup representing the end of the scene. 
