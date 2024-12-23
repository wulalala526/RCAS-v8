RCAS-YOLOv8 re-implementation using PyTorch

### Options

For each option you must to download the repository for YOLOv8

### Installation

```
conda create -n YOLO8-RCA python=3.8
conda activate YOLO

```

### Train

* Configure your dataset path in `main.py` for training
* Run `bash main.sh $ --train` for training, `$` is number of GPUs

### Test

* Configure your dataset path in `main.py` for testing
* Run `python main.py --test` for testing



#### Reference

* https://github.com/ultralytics/yolov5


#### DataSet
https://github.com/InsulatorData/InsulatorDataSet
