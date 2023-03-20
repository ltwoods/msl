This directory contains the following subdirectories and files:

README.txt				This file.
wlaslalt_train_info.csv			Our WLASL-alt train split info.
wlaslalt_val_info.csv			Our WLASL-alt val split info.
wlaslalt_test_info.csv			Our WLASL-alt test split info.
010_classes/all_info_010.csv		Our WLASL-alt all info for 10 classes.
010_classes/train_info_010.csv		Our WLASL-alt train split info for 10 classes.
010_classes/val_info_010.csv		Our WLASL-alt val split info for 10 classes.
010_classes/test_info_010.csv		Our WLASL-alt test split info for 10 classes.
050_classes/all_info_050.csv		Our WLASL-alt all info for 50 classes.
050_classes/train_info_050.csv		Our WLASL-alt train split info for 50 classes.
050_classes/val_info_050.csv		Our WLASL-alt val split info for 50 classes.
050_classes/test_info_050.csv		Our WLASL-alt test split info for 50 classes.
100_classes/all_info_100.csv		Our WLASL-alt all info for 100 classes.
100_classes/train_info_100.csv		Our WLASL-alt train split info for 100 classes.
100_classes/val_info_100.csv		Our WLASL-alt val split info for 100 classes.
100_classes/test_info_100.csv		Our WLASL-alt test split info for 100 classes.
300_classes/all_info_300.csv		Our WLASL-alt all info for 300 classes.
300_classes/train_info_300.csv		Our WLASL-alt train split info for 300 classes.
300_classes/val_info_300.csv		Our WLASL-alt val split info for 300 classes.
300_classes/test_info_300.csv		Our WLASL-alt test split info for 300 classes.

Each wlaslalt_*_info.csv file contains the following fields:
video_id,class,sequence_length

Each *_classes/*_info_*.csv file contains the following fields:
video_id,class

where

`video_id` is the original WLASL dataset video ID
`class` is the replacement class label after incorporating the WLASL-alt changes and renumbering
`sequence_length` is the number of frames per sequence with valid data before being padded.
