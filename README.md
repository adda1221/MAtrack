# MAtrack

This is the implementation of MAtrack.    
This code is based on DETR: [[link]](https://github.com/facebookresearch/detr).


## Dependencies
+ PyTorch 1.7.0
+ torchvision 0.8.1
+ cudatoolkit 10.2  
+ easydict
+ cython


## DataSets

${MAtrack_ROOT}
 -- data
     -- Lasot
         |-- airplane
         |-- basketball
         |-- bear
         ...
     -- GOT10k
         |-- test
         |-- train
         |-- val
     -- COCO
         |-- annotations
         |-- images
     -- TrackingNet
         |-- TRAIN_0
         |-- TRAIN_1
         ...
         |-- TRAIN_11
         |-- TEST
