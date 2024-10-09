# The work will soon be open source

## Registered DroneVehicle Dataset

Due to slight misalignments between some RGB and IR image pairs in the DroneVehicle Dataset (https://github.com/VisDrone/DroneVehicle), we filter out image pairs that are roughly aligned based on bounding box information to create a new dataset. This registered dataset is constructed as follows:

    DroneVehicle_align_crop/
    │
    ├── imgs/
    │   ├── train_img/
    │   │      └── ir/*.jpg
    │   │      └── vis/*.jpg
    |   ├── val_img/
    │   │      └── ir/*.jpg
    │   │      └── vis/*.jpg
    |   └── test_img/
    │          └── ir/*.jpg
    │          └── vis/*.jpg
    └── labels/
        ├── train_labels/*.txt
        ├── val_labels/*.txt
        └── test_labels/*.txt

The training set contains 3,098 image pairs, while the test set and validation set consist of 1,543 and 256 image pairs. The dataset includes five categories: car, truck, bus, van, and freight car.

Notely, the original images have white borders of 100 pixels around their edges. By removing these white borders, we obtain images with a size of 640x512 pixels. The format for the annotation boxes is as followes: (x1, y1, x2, y2, x3, y3, x4, y4, category). These labels keep the original values. Please subtract 100 pixels in evaluation. This dataset is available on the download page.

## BaiduYun

Please refer to the download page (https://pan.baidu.com/s/1pEIViccS37CnDIE9PtZKyw?pwd=r1ck).

## GoogleDrive

Googledrive link will be released soon.

If you have any questions, feel free to contact me (<jinfuli@bit.edu.cn>).
