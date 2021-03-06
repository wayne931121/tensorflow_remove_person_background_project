# tensorflow_person_image_remove_background

*   [Model weights url](https://drive.google.com/drive/folders/1wU1Np8thAQ5qBpwmUTCcIWpS9772Nror?usp=sharing)
*   Object Detection: SSD ResNet50 V1 FPN 640x640 (RetinaNet50)
*   Image Segmentation: Unet

## Target

*   Remove person images or videos background
*   此模組適合正面且單人的圖片
*   This model is suitable for frontal and single-person images.

## Using

*   Python
*   Tensorflow
*   Opencv
*   Numpy
*   and so on.

## What our code do?

1. Object Detection > Get boxes
2. Image Segmentation in each detected image boxes > Get mask
3. Remove background > Result

## You can try this model.

*   [https://youtu.be/C9AffviLrxo](https://youtu.be/C9AffviLrxo)
*   [https://colab.research.google.com/drive/1rDcVczczKy8IbUnfA4aAVrM_AKSwuJl7](https://colab.research.google.com/drive/1rDcVczczKy8IbUnfA4aAVrM_AKSwuJl7)

## References

*   [https://www.tensorflow.org/?hl=zh-tw](https://www.tensorflow.org/?hl=zh-tw)
*   [https://github.com/tensorflow/models](https://github.com/tensorflow/models)
*   [https://github.com/tensorflow/models/blob/master/research/object_detection/colab_tutorials/eager_few_shot_od_training_tf2_colab.ipynb](https://github.com/tensorflow/models/blob/master/research/object_detection/colab_tutorials/eager_few_shot_od_training_tf2_colab.ipynb)
