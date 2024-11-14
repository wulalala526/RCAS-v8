RCAS-YOLOv8 re-implementation using PyTorch

### Installation

```
conda create -n YOLO python=3.8
conda activate YOLO
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch-lts
pip install opencv-python==4.5.5.64
pip install PyYAML
pip install tqdm
```

### Train

* Configure your dataset path in `main.py` for training
* Run `bash main.sh $ --train` for training, `$` is number of GPUs

### Test

* Configure your dataset path in `main.py` for testing
* Run `python main.py --test` for testing



#### Reference

* https://github.com/ultralytics/yolov5
* https://github.com/ultralytics/ultralytics
