# allegro\_lvl\_1 dataset
This dataset was used to benchmark in-hand manipulation level-1 on the allegro hand.

## How to use the dataset
The dataset is in the spreadsheet (.ods) file named `relaxed-rigidity.ods`. The dataset contains the following columns:


| Column name                 | Format                                                                                                                                                                        | Description                                                                                                                            |
|--------------------------- |----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |-------------------------------------------------------------------------------------------------------------------------------------- |
| Object                      | string                                                                                                                                                                        | Name of the YCB object                                                                                                                 |
| AR tag offset               | x,y,z                                                                                                                                                                         | Offset x,y,z from YCB object mesh in meters                                                                                            |
| Initial grasp configuration | index\_j0, index\_j1, index\_j2, index\_j3, middle\_j0, middle\_j1, middle\_j2, middle\_j3,ring\_j0, ring\_j1, ring\_j2, ring\_j3, thumb\_j0, thumb\_j1, thumb\_j2, thumb\_j3 | Joint configuration of the allegro hand at the initial grasp in radians                                                                |
| Fingers                     | n0,n1,n2,n3..                                                                                                                                                                 | fingers used for manipulation (0-index, 1-middle, 2-ring, 3-thumb)                                                                     |
| Initial palm pose         | x,y,z,tx,ty,tz                                                                                                                                                                | Pose of the palm at the initial grasp, position given by x,y,z in meters and tx,ty,tz are euler RPY in radians                       |
| Desired palm pose         | x,y,z,tx,ty,tz                                                                                                                                                                | Goal pose for the palm, position given by x,y,z in meters and tx,ty,tz are euler RPY in radians                                      |
| Final palm pose           | x,y,z,tx,ty,tz                                                                                                                                                                | Reached Pose of the palm using \`Relaxed-Rigidity\` method,  position given by x,y,z in meters and tx,ty,tz are euler RPY in radians |

## Benchmark results
This dataset has been used for benchmarking in-hand manipulation level 1. Refer to the below pdf for more info:
[Results URL](https://robot-learning.cs.utah.edu/_media/project/bih_demo_lvl1.pdf)

## Citing
If you use the dataset, cite the following publication,

*Sundaralingam B, Hermans T. Relaxed-rigidity constraints: kinematic trajectory optimization and collision avoidance for in-grasp manipulation. Autonomous Robots. 2019 Feb 15;43(2):469-83.*

```
@article{sundaralingam2019relaxed,
  title={Relaxed-rigidity constraints: kinematic trajectory optimization and collision avoidance for in-grasp manipulation},
  author={Sundaralingam, Balakumar and Hermans, Tucker},
  journal={Autonomous Robots},
  volume={43},
  number={2},
  pages={469--483},
  year={2019},
  publisher={Springer}
}
```

