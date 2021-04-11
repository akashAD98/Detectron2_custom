# Detectron2_custom



# For Object detection
1.use labelimg software for drawing bbox on top of images

2.select XML/PascalVOC format for doing annotation

3.Seprate the output in different folder ex. train==>> all images ; trainannotaion==>> xml format

4.we can not use XML/VOC format for object detecton in detectron2 , so we are converting xml to json using this file


```
python voc2coco.py train_annotations/ output.json
```
