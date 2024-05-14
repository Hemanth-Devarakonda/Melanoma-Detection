# Melanoma Detection
> This project is to build a CNN model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is part of the Upgrad ML AI programme.
- It involves data classification and understanding.
- Build vanila CNN model and evaluate metrics.
- Add Augmentation to the data set, rebuild model and evaluate metrics.
- Adding Dropout layers to verify if the model accuracy gets modified.
- Adding additional samples using Augmentor pipeline and building a model upon the same to evaluate the metrics. 


## Conclusions
- Vanila CNN model's output accuracy on the training set was way higher than the validation set's accuracy indicating an overfitted model.
- Augmentation on the data helped did not help increasing the accuracy on validation level.
- Dropout layer addition when building the model reduced the gap between training set accuracy and validation set accuracy but overall wasn't an ideal model.

## Technologies Used
- Keras
- TensorFlow
- pathlib
- google colab to mount google drive for dataset.


## Contact
Created by [Hemanth-Devarakonda] - feel free to contact me!
