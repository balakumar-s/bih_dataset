# Benchmarking In-Hand Manipulation Dataset
This repo contains dataset for benchmarking in-hand manipulation on different robot platforms. More details are available at <https://robot-learning.cs.utah.edu/project/benchmarking_in_hand_manipulation>

## Repo structure:
- The hand poses dataset exists in the folder `dataset`, a readme exists that discuses the dataset and how to use it.
- Initial and desired contact mesh regions are available at the provided URL.
- Additionally, results on robot platforms are available inside the folder named `results`.
- The subfolders in `results` have the name `ROBOTNAME_lvl_NO`, where `ROBOTNME` refers to robot platform and `NO` refers to the level of benchmarking in-hand manipulation.

## Benchmarked Methods

### Level I
1. Relaxed-Rigidity
2. Relaxed-position
3. Relaxed-position-orientation 
4. Point Contact with Friction
5. IK-Rigid

### Level III
1. Dexterous Manipulation Graphs

## To Contribute:
The provided dataset works sufficiently well for human sized robotic hands. We encourage the research community to run their in-hand manipulation scheme with our dataset on the YCB objects set and submit their results as a pull request. 
