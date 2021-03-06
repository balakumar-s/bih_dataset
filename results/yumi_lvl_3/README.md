# yumi\_lvl\_3 dataset
This dataset was used to benchmark in-hand manipulation level-3 on the YuMi robot.

## How to use the dataset
The dataset is in the spreadsheet (.ods) file named `DMG.ods`. The dataset contains the following columns:

| Column name         | Format      | Description                                                             |
|------------------- |----------- |----------------------------------------------------------------------- |
| Object              | string      | name of YCB object                                                      |
| Task                | number      | task number used to obtain start & goal contact region                  |
| Initial contact1    | x,y,z       | initial contact position of gripper finger 1 in meters w.r.t object     |
| Initial contact2    | x,y,z       | initial contact position of gripper finger 2 in meters w.r.t object     |
| Initial orientation | qx,qy,qz,qw | initial orientation of gripper w.r.t. object in unit quaterion          |
| Desired contact1    | x,y,z       | desired contact position of gripper finger 1 in meters w.r.t object     |
| Desired contact2    | x,y,z       | desired contact position of gripper finger 2 in meters w.r.t object     |
| Desired orientation | qx,qy,qz,qw | desired orientation of gripper w.r.t. object in unit quaterion          |
| Final contact1      | x,y,z       | DMG planned contact position of gripper finger 1 in meters w.r.t object |
| Final contact2      | x,y,z       | DMG planned contact position of gripper finger 2 in meters w.r.t object |
| Final orientation   | qx,qy,qz,qw | DMG planned orientation of gripper w.r.t. object in unit quaterion      |
## Benchmark results
This dataset has been used for benchmarking in-hand manipulation level 3. Refer to the below link for more info:
[Results URL](https://robot-learning.cs.utah.edu/_media/project/bih_demo_lvl3.pdf)

## Citing
If you use the dataset, cite the following publication,

*Cruciani S, Smith C, Kragic D, Hang K. Dexterous manipulation graphs. In2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2018 Oct 1 (pp. 2040-2047). IEEE.*


```
@inproceedings{cruciani2018dexterous,
  title={Dexterous manipulation graphs},
  author={Cruciani, Silvia and Smith, Christian and Kragic, Danica and Hang, Kaiyu},
  booktitle={2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={2040--2047},
  year={2018},
  organization={IEEE}
}
```

