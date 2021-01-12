# Face-Mask-Detection

## Downloading Classification Dataset 
```python
!gdown --id 1nmLc8_Xgj7jFBffjKqsMXYXWZpiTzgut
!unzip /content/Dataset.zip
!gdown --id 1H3anHpuKHOJBfOU_AUZ4vci9IsCeA8Zp
!unzip /content/CrowdMaskDetection.zip
```

## Downloading Kaggle FaceMask Dataset
```python
! mkdir ~/.kaggle
! cp kaggle.json ~/.kaggle/
! chmod 600 ~/.kaggle/kaggle.json
!kaggle datasets download -d andrewmvd/face-mask-detection
! mkdir train
! unzip face-mask-detection.zip -d train
```
## Final Testin Imges
```python
! git clone https://github.com/biplav-s/image-mask-estimate
```

## Refrences

* [MTCNN library](https://pypi.org/project/fdet/)
* [Xception](https://www.tensorflow.org/api_docs/python/tf/keras/applications/Xception)
* [MTCNN Paper](https://arxiv.org/ftp/arxiv/papers/1604/1604.02878.pdf)
* [Xception paper](https://arxiv.org/pdf/1610.02357.pdf)
* [Yolov5](https://github.com/ultralytics/yolov5)
