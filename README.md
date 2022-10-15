# YOLOv5-CoreML-Converter
Recent YOLOv5 export.py do not support train model. For CoreML conversion, export.py need train mode exporting.
This export.py can export 3 multiarray without NMS and detect layer.
After replacing the original export.py to this, you can convert CoreML model using following scripts

Here is the blog that I followed to run this script:
https://rockyshikoku.medium.com/convert-yolov5-to-coreml-also-add-a-decode-layer-113408b7a848

https://colab.research.google.com/drive/1uR738UTlzI7apqeN0qr6mQ5ke_a5SKa8?usp=sharing


I made conveter.py referencing above script.
YOLOv5CoreMLConverter.py can get argument
 YOLOv5CoreMLConverter.py [-h] [-input MODEL_INPUT_PATH]
                                [-output MODEL_OUTPUT_DIRECTORY]
                                [-name MODEL_OUTPUT_NAME] [-quant]
                                [-size IMGSIZE] [-label CLASSNAME]

to use this script , to run following
YOLOv5CoreMLConvertProcess.ipynb
