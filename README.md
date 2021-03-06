# Dijkstra_Algorithm
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Implementation of Dijkstra algorithm for robot path planning
<p align="center">
  <img src="https://github.com/Pruthvi-Sanghavi/Dijkstra_Algorithm/blob/main/result/result_point.png">
</p>

## For execution in windows
### Dependencies

#### Numpy
Open the command prompt and type:
```
pip install numpy
```

#### Matplotlib
Open the command prompt and type:
```
pip install matplotlib
```

### Running from zip - 

- Download zip folder Dijkstra_Algorithm.zip
- Exract the zip folder

- Open command prompt
```
cd (directory where zip is extracted)
cd Dijkstra_Algorithm-master/src
python Dijkstra_point.py (for point robot)
python Djikstra_rigid.py (for rigid robot) 
```
#### for point robot
- After the code execution begins
- Enter the starting coordinates separated by spaces
- Enter the goal coordinates separated by spaces
- Hit enter

#### for rigid robot
- After the code execution begins
- Enter the radius of the robot
- Enter clearance
- Enter the starting coordinates separated by spaces
- Enter the goal coordinates separated by spaces
- Hit enter

#### TODO

1. [ ] Add unit tests
2. [ ] Check Linux Implementation
3. [ ] ROS Implementation
