## Depth-prediction-completion

### Depth prediction & Depth completion
* depth prediction:   
-- input: RGB image, ground truth  
-- output: dense depth map  
-- dataset  
-- metrics:   
![metrics](data/metric.png)


* depth completion:  
-- input: sparse raw depth data, RGB image(optional), ground truth (still sparse but denser than the raw data)  
-- output: dense depth map  
-- dataset: [KITTI Depth Completion](http://www.cvlibs.net/datasets/kitti/eval_depth.php?benchmark=depth_completion)  
-- metrics:   
![metrics2](data/metric2.png)


