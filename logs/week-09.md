# Week 9

**Dates:** 07-27 to 07-31

## Goals
- decrease variance with model and actions performed
- improve success rate of model


## Approach and Implementation
- I increased Kp in the pid controller of the arm and immediately increased performance
- I changed the model to predict joint angles rather than end effector position this should allow the model to learn the PID controller and the dynamics of the entire system better


## Results
- Changing the Kp made all models perform at ~80% success rate in the clean environment but will probably not transfer in the real world correctly. To address this I trained the model to output joint angles directly to learn the inverse kinmeatics directly. This also gave me a 80% success rate and will hopefully perform better sim2real. Additonally, the DINOv2 model still performs worse but I trained it for longer and will test next week if that improves performance. 


## Notes
- I had to move out so I was not able to work as much as previous weeks 
