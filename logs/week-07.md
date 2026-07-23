# Week 7

**Dates:** 07-13 to 07-17

## Goals
- Get the model to perform better in the training environment
- Get the model to perform better in environments outside the trianing environment


## Approach and Implementation
- I modified the act policy to use images instead of point clouds and that immediataly increase model performance
- I then swapped what data I was using to instead use data from mimicgen to rule out data being the problem.
- I also found a bug in my transformer causing the multi head attention mechanism to effectivly be single head
- I changed the vision backbone to highlight important objects so that the model can only learn from those and hopefully this will lead to better generalization in environments with additional objects


## Results
- The model is starting to perform better in the training environment
- Next week I will focus on how I can get it to perform well in the training environment and better in unseen environments
- I believe the way I am doing the object tracking can be improved and I will read more about other approachs next week


## Notes


