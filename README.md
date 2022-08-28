## MTT-System-GNN-Tracker


## Project Description
This project presents implementation of a multiple object tracking system. We implemented Global Nearest Neighbour Tracker in conjuction with EKF to track constant velocity targets. We formulate multiple hypotheses using k-best algorithm for 2D assignment of measurement-to-tracks. The probability of target existence is used to confirm/delete and maintain tracks in the track management system. 



<p align="center">
  <img src="/Media/map3.jpg" />
</p>

## Platform
* C++

## Implementation
 
Navigate to the ```build``` folder

```$ mkdir build```

```$ cd build```

```$ cmake ..```

```$ make ```

```$ ./main ``` 
