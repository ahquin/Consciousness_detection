# Consciousness detection via visible and infrared imaging
This project presents an algorithm (link article) that detects consciousness based on human mobility using visible (RGB) and infrared imaging (IRT).

This project was developed using Python 3.7 and the algorithm uses the the open source Mask R-CNN developed by He et al., and image processing techniques.


## Method
Example of the mobility classification of the RGB data. 
| ![This is an image](https://github.com/dddqqq/Consciousness_detection/blob/main/media/Figure%203.png) |
|:--:| 
| <b>  
 <b> Intermediary RGB images throughout the algorithmic process: a) the original RGB frame, b) the mask and bounding box given from mask R-CNN, c) the binary skeletonized mask, d) the white grid on the gray image, e) the processed image prepared for selection of feature points, f) the selection of feature points, and g) the movement lines in between two frames of the feature points (essentially “head” movement). The obtained movement signal through time is displayed in the graphic, and, in this case, the person is classified as “moving.” </b>|

The following videos exemplify the whole method through the videos of 30s. Tracking is performed at each second of the videos.
RGB video ![RGB video](https://github.com/dddqqq/Consciousness_detection/blob/main/media/rgb_lay_Head_covered.mp4)
IRT video ![IRT video](https://github.com/dddqqq/Consciousness_detection/blob/main/media/irt_lay_Head.mp4)





## Installation:
- Python 3.7
- Pycocotools from philferriere [(Pycocotools)](https://github.com/philferriere/cocoapi)
- Cuda 10.0
- Mask R-CNN from He et al.  [(Mask R-CNN)](https://github.com/matterport/Mask_RCNN)


## Citation
Use this bibtex to cite this repository:

@misc{queirospokee,
    author       = {Queirós Pokee et al.},
    title        = {{Consciousness detection on injured simulated patients using manual and automatic classification via visible and infrared imaging}},
    month        = ,
    year         = ,
    doi          = {},
    version      = {1.0},
    publisher    = {},
    url          = {}
    }
