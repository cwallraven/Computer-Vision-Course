# Computer Vision Course 
This will be the repository for the Computer Vision Course for the fall semester 2019 taught at KU.

So far, this is based on the code and structure from the [OpenCV 3 Computer Vision with Python Cookbook](https://www.packtpub.com/application-development/opencv-3-computer-vision-python-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781788474443), published by [Packt](https://www.packtpub.com/?utm_source=github). 

## About the course

The course is a mix of fundamental theory and applications. It uses

- Python 

- OpenCV, as a cross-platform library for computer vision. 

Examples of the code:
```
import argparse
import cv2
parser = argparse.ArgumentParser()
parser.add_argument('--path', default='../data/Lena.png', help='Image path.')
params = parser.parse_args()
img = cv2.imread(params.path)
```


## Course structure

Image formation 

Camera optics and calibration

The structure of pixels and images

Low-level processing
- Histograms
- Filtering and enhancing
- Feature detection

Mid-level processing
- Segmentation
- Shape processing
- Optic flow
- Stereo processing
- Tracking

High-level processing
- Recognition and classification
- Face analysis (detection, identification, expressions, age, attractiveness)
- Describing pictures (deep learning)
- Making pictures (GANs)
- The limits of deep learning and where to go next




## Suggested reading

### Suggestions and Feedback

