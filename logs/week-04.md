# Week 4

**Dates:** 06-22 to 06-26

## Goals
- finish part 3 of the act model
- reimplment a vanilla transformer because act makes modifications that require a rewrite of the transformer
- understand resnet and convolution to see how I can replace that with a point cloud encoder

## Approach and Implementation
- I read the original transformer paper in depth and annotated it
- I read the annotated transformer to see the proper way to create the transformer in code
- I created the phase 3 of the act model except for the transformer part
- I read about convolution and pointnet++ which I will use instead of resnet because it creates a feature map of the point cloud. 



## Results
- The transformer I made works and trains correctly. I verified that given a small dataset it can learn translation and given arrays that are reversed it can learn the reversing algorithm
- I also verified that act works but I am not sure if it generates good trajectories and I will do that next week


## Notes


