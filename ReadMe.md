# Raccoon Detector Dataset

Dataset from [experiencor/raccoon_dataset](https://github.com/experiencor/raccoon_dataset)

* annotations: contains the xml files in PASCAL VOC format
* images: contains the image data in jpg format
* raccoon_classes.txt: classes(only raccoon)
* raccoon_test.txt: selected test dataset
* raccoon_train.txt: selected training dataset
* raccoon_train_data.txt: Customized description file for training dataset
* raccoon_test_data.txt: Customized description file for test dataset

Customized description file:
One row for one image;
Row format: image_file_path box1 box2 ... boxN;
Box format: x_min,y_min,x_max,y_max,class_id (no space).
