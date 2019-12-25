# Hand Poses Dataset
This dataset contains initial and desired palm pose for benchmarking in-hand manipulation. 

## How to use the dataset
The dataset is in the spreadsheet (.ods) file named `lvl_1.ods`. The dataset contains the following columns:


| Column name       | Format         | Description                                                                                                                          |
|-------------------|----------------|--------------------------------------------------------------------------------------------------------------------------------------|
| Object            | string         | Name of the YCB object                                                                                                               |
| Initial palm pose | x,y,z,tx,ty,tz | Pose of the palm at the initial grasp, position given by x,y,z in meters and tx,ty,tz are euler RPY in radians                       |
| Desired palm pose | x,y,z,tx,ty,tz | Goal pose for the palm, position given by x,y,z in meters and tx,ty,tz are euler RPY in radians                                      |


Since the hand frame changes for different robotic hands, the goal of our benchmark is to obtain the relative change between the initial and desired hand poses. More details are available in our publication.
