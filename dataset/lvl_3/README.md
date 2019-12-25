# lvl\_3 dataset
This dataset contains desired orientation and desired contacts for benchmarking level 3 in-hand manipulation was used to benchmark in-hand manipulation level 3.

## How to use the dataset
The dataset is in the spreadsheet (.ods) file named `lvl_3.ods`. The dataset contains the following columns:

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

