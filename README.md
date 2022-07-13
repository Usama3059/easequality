
# Easequality

Make the Data and Models Quality easy for everyone

Easequality is basically a High level Wrapper which connects your Data/Model with various Quality Tools, Hence you can evaluate the Data/Model quality with few lines of code.





![Logo](https://i.ibb.co/NjF0MSX/Screenshot-2022-07-07-225745.jpg)


## Updates

- The code will be released soon! Please stay tuned! :blush:


## Installation

To install

```bash
  git clone https://github.com/Usama3059/easequality.git
  cd Easequality
```
    
## Example/Usage

To run tests, run the following command, we are evaluating on the BCCD Dataset and Yolov5

```python
#Example for Yolov5 Model
from yolo import yolo_quality
cls_dict = {
        0: 'RBC',
        1: 'WBC',
        2: 'Platelets'}


yolo = yolo_quality( train_dir_path='train',
                     test_dir_path='valid',
                     model_path='model.pt',
                     class_dict = cls_dict)

yolo.result()

```


## Integeration

- Supports MSCOCO, PascalVOC, Yolo, Yolo Darknet etc

- Supports Fastai Classification

- Supports Timm Models

- Supports Detectron2

- Supports Yolov5


## On going tasks

- Code release for everyone

- Quick Summary

## 🚀 About Me
Hi, I'm Usama Altaf Zahid mainly work as Computer vision Engineer. I like working with AI models and building Computer vision based problem solving products. This repo is basically a helpful tool to easily and rapidly evaluate and improve the Data/Model Quality, Hence to build more robust Models with very less training process iterations


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/uaz-3059/)


## Contributing

Contributions are always welcome!

If you have any feedback, please reach out to us at uazch902@gmail.com



