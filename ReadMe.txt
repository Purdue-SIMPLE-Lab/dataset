Usage of this dataset:

This dataset is stored as the format of Pascal VOC data. The sturcture of the folder is as follows.

Integrated-Data
|----Annotations
|          |-------*.xml (all the annotation info for each images)
|----ImageSets
|          |-------Main
|                        |----------*.txt (tell if each image includes the object of the certain category. Note: only left_turn_train.txt and left_turn_val.txt are valid)
|----JPEGImages
         |-------*.JPG (all the image files)

Please use the ./scripts/mark_annotation.py to convert the dataset into the files that can be recognized by the codes. Be careful with the parameters setting within the codes.