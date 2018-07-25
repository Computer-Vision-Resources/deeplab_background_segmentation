# DeepLab on Android
DeepLab is a state-of-art deep learning model for semantic image segmentation, where the goal is to assign semantic labels (e.g., person, dog, cat and so on) to every pixel in the input image. Here is mobile version running on Android devices.

Here is demo screen recording.

<img src=".github/deeplab_demo.gif" width="280" height="498" alt="DeepLab Demo"/>

## How to run
Download the frozen graph mobilenetv2_coco_voc_trainaug from [Deeplab github](https://github.com/tensorflow/models/blob/master/research/deeplab/g3doc/model_zoo.md) and put to assets folder.

## Known issues
Crashes with the exception no _OpKernel was registered to support Op 'Slice' with these attrs_

## License
Forked from https://github.com/dailystudio/ml/tree/master/deeplab
[Apache License 2.0](LICENSE)
