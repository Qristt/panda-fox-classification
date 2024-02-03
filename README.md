## Panda fox Classification Model


![Project Banner](https://github.com/Qristt/panda-fox-classification.git)

#

### Task Description

The goal of the task was to create a model that would predict what animal was given a picture. The images used to create this model were obtained from websites. The goal of the model was to accurately determine the name of the animal. It was very important for the model to perform the prediction well, considering that the data provided is a small part of the whole.

---


### Tech Stack

<img align="left" alt="Java" width="30px" style="padding-right:20px;" src="https://github.com/GorPiliposyan/subway-ticket-barrier-state-detection/blob/main/Images/Python-logo-notext.svg"/>
<img align="left" alt="Java" width="30px" style="padding-right:20px;" src="https://github.com/GorPiliposyan/subway-ticket-barrier-state-detection/blob/main/Images/PyTorch_logo_icon.svg"/>
<img align="left" alt="Java" width="100px" style="padding-right:20px;" src="https://github.com/GorPiliposyan/subway-ticket-barrier-state-detection/blob/main/Images/UltralyticsYOLO_full_blue.svg"/>
<img align="left" alt="Java" width="30px" style="padding-right:20px;" src="https://github.com/GorPiliposyan/subway-ticket-barrier-state-detection/blob/main/Images/OpenCV_Logo.svg"/>
<br />

#

- **Python**
- **PyTorch**
- **Ultralytics YOLOv8**
- **OpenCV**

#

### Approach Overview

- **Model Preparation Jupyter Notebook:** The process of creating the classification model was detailed in the `model_preparation.ipynb` notebook. This notebook includes comprehensive steps for data preparation, model training, and evaluation. Comments throughout the notebook elaborate on key decisions and metrics supporting the model's adequacy.
- And model_structure.ipynb` is the model.


#

### Web App

**Web application coming very soon!**

#


### Deliverables

**Main files:**
- `model_preparation.ipynb`: Detailed Jupyter Notebook showcasing in detail the model creation process with relevant comments and a discussion section in the end.
- `model_structure.ipynb`: Python code file, our model`.
- `yolov8x_cls_custom.pt`: Ultralytics YOLOv8 custom trained 'yolov8x-cls.pt' model weights file. Necessary to run `model_run.py` file.

**Extra files:**
- `utils`: Folder with some helper functions I have used for "model_preparation.ipynb"
- `simple_images`: Dataset folder with the original and augmented images, split into train/val/test folders. (test images only in original folder)
- `runs`: Folder with training images.
