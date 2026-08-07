# Week 8

**Dates:** 07-20 to 07-24

## Goals
- improve model performance in training environment
- Figure out object detection model
- Finish my poster for poster symposium

## Approach and Implementation
- implemeted DINOv2 with LoRA into a casual multi head attention block to utilize VFM knowledge with transformer action head
- tested with 50 trials in each environment too keep error low


## Results
- trials came back that all models perform around the same in the clean environment and then in cluttered dinov2 performs worse. I don't know the exact reason for this but after replaying my dataset actions through mujoco they also succeed around 45% of the time. This means that something about the simulator is not accurate and there is a lot of variance with if correct output from my model will produce correct actions.


## Notes


