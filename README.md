# YOLOv5-export.py-withTrainMode
Recent YOLOv5 export.py do not support train model. For CoreML conversion, export.py need train mode exporting.
This export.py can export 3 multiarray without NMS and detect layer.
After replacing the original export.py to this, you can convert CoreML model using following scripts

https://colab.research.google.com/drive/1uR738UTlzI7apqeN0qr6mQ5ke_a5SKa8?usp=sharing
