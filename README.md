# UI-Elements-Detection Using YOLOv5
---
<br>
In this repository,the UI element detection using the YOLOv5 architecture on dataset imported from roboflow using this snippet.<br>

```
from roboflow import Roboflow
#This api key to download the dataset
rf = Roboflow(api_key="N5xD3OgJvMzngIKg6nyR")
project = rf.workspace("ulkesh").project("web-elements-rn0zn")
dataset = project.version(2).download("yolov5")
```
<br>

# Dataset
There are 13 labels in the dataset and contains around 65 images.<br>

# Code <br>
The code implementation is provided in the train.ipynb file.
<br>
# Evaluation Metrics <br>
The metrics used in the evaluation are :<br>
1.Mean Average Precision<br>
2.Precision<br>
3.Recall<br>
<br>
# Results <br>
The results are provided in the results.csv.<br>
The results can be better visualized in the results.png<br>



