# YOLOv5-CoreML-Converter
Recent YOLOv5 export.py do not support train model. For CoreML conversion, export.py need train mode exporting.
This export.py can export 3 multiarray without NMS and detect layer.
After replacing the original export.py to this, you can convert CoreML model using following scripts

Here is the blog that I followed to run this script:

https://rockyshikoku.medium.com/convert-yolov5-to-coreml-also-add-a-decode-layer-113408b7a848

https://colab.research.google.com/drive/1uR738UTlzI7apqeN0qr6mQ5ke_a5SKa8?usp=sharing


I made YOLOv5CoreMLConverter.py referencing above script.
This conveter can get argument

to use this script , to run following

YOLOv5CoreMLConvertProcess.ipynb


YOLOv5CoreMLConverter.py is for YOLOv5 P5 model

YOLOv5P6CoreMLConverter.py is for YOLOv5 P6 1280image size model
