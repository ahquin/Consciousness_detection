# Consciousness detection via visible and infrared imaging
This project presents an algorithm (link article) that detects consciousness based on human mobility using AI and image processing techniques using visible (RGB) and infrared imaging (IRT).

This project was developed using Python 3.7 and it uses the open source Mask R-CNN developed by He et al.


## Method
Example of the mobility classification of RGB data. ![This is an image](https://github.com/dddqqq/Consciousness_detection/blob/main/media/Figure%203.png)

The following videos examplify the whole method through the videos of 30s. Tracking is performed at each second of the videos.
RGB video ![RGB video](https://github.com/dddqqq/Consciousness_detection/blob/main/media/rgb_lay_Head_covered.mp4)
IRT video ![IRT video](https://github.com/dddqqq/Consciousness_detection/blob/main/media/irt_lay_Head.mp4)




## Installation:
- Python 3.7
- Pycocotools from philferriere [GitHub Pages](https://github.com/philferriere/cocoapi)
- Cuda 10.0
- Mask R-CNN from He et al.  [GitHub Pages](https://github.com/matterport/Mask_RCNN)


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
