# Violence Detection with YOLOv11
This project demonstrates a Violence Detection system trained using the YOLOv11 small model. The model was fine-tuned using the new_violence_dataset from Roboflow Universe "https://universe.roboflow.com/teepakorn-hwkus/new_violence_dataset" and trained on an Intel Core i7-12th generation CPU.

##  Features
* Real-time violence detection using YOLOv11.
* Fine-tuned for violence scenarios with publicly available datasets.
* Easy installation and usage instructions for quick deployment.
## Installation
Clone the Repository:
```
git clone https://github.com/mohamedelsayed0001/Violence-Detection.git
cd Violence-Detection
```
Install Dependencies:

Ensure you have Python installed (preferably Python 3.8 or later). Then, install the required packages:

```
pip install ultralytics opencv-python-headless
```
## Training the Model

The training was performed using an Intel Core i7-12th generation CPU. For better performance, it's recommended to use a GPU for future training sessions.
## Future Work
* Further Fine-Tuning: The model is currently trained on a relatively small dataset, so additional fine-tuning could help improve accuracy and performance.
* Data Augmentation: Collecting more diverse samples from different scenarios and performing data augmentation will help the model generalize better.
* Extended Training: Increasing the number of training epochs and utilizing a GPU can significantly enhance the model's ability to detect violence more accurately in real-time.
