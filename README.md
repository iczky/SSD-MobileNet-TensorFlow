# SSD-MobileNet-TensorFlow
This is the python notebook of how i created the model from SSD MobileNet using TensorFlow and convert it to TFLite

What im creating is the model to detecting maturity of Oil Palm Fruit.

My dataset for preparing this dataset is over 5k images of piles Oil Palm Fruits

Model evaluation test result is:

    I1121 13:23:30.430203 139685949912960 model_lib_v2.py:1015] Eval metrics at step 50000 
    INFO:tensorflow: + DetectionBoxes_Precision/mAP: 0.739317 
    I1121 13:23:30.486999 139685949912960 model_lib_v2.py:1018] + DetectionBoxes_Precision/mAP: 0.739317 
    INFO:tensorflow: + DetectionBoxes_Precision/mAP@.50IOU: 0.969898 
    I1121 13:23:30.488476 139685949912960 model_lib_v2.py:1018] + DetectionBoxes_Precision/mAP@.50IOU: 0.969898 
    INFO:tensorflow: + DetectionBoxes_Precision/mAP@.75IOU: 0.884218 
    I1121 13:23:30.489448 139685949912960 model_lib_v2.py:1018] + DetectionBoxes_Precision/mAP@.75IOU: 0.884218

Overall the model is really good at detecting maturity of Oil Palm Fruit
