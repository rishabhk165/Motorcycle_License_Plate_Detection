# Motorcycle License Plate Extraction when Rider is not Wearing a Helmet

This project focuses on extracting motorcycle license plates when the rider or back sitter is not wearing a helmet.

## Overview

I use the YOLOv5 algorithm to detect the rider, license plate, and rider's head. Then, utilizing the ResNet50 image classifier, I determine whether the rider is wearing a helmet or not. If not wearing a helmet, the system saves their license plate number in an image folder and captures the rider's image in a separate folder.



## Download Model and Necessary Files

### YOLOv5 Weight Files
- [Small Version](https://drive.google.com/file/d/1LbX-YRBTgJZEIqQqmCpNq4CNQzoiA8p5/view?usp=sharing)
- [Medium Version](https://drive.google.com/file/d/16ZDjUcX7vXQYPJ557dooN0em4mJmbJt7/view?usp=sharing)

### Classification Model (ResNet50)
- [Download Model](https://drive.google.com/file/d/1OuOpgq99E5VKPtwUuFZ0GGety3YWjIQn/view?usp=sharing)

## Getting Started

1. Download the YOLOv5 weight files and the classification model.
2. Place all downloaded files in the main folder of this project.
3. Run the code to start extracting license plates based on helmet detection.

Feel free to explore, contribute, and enhance the capabilities of this project!
