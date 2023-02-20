# Computer Vision

![vision_wizard](https://user-images.githubusercontent.com/38589666/218272338-1f30e72c-a057-4a42-8253-e4b34848ad3c.png)

@bammer awakens his inner arcane wizard while studying computer vision!

## Environment

- Windows 11

```python
> conda -V
conda 22.9.0
> python -V
Python 3.9.13 (main, Aug 25 2022, 23:51:50) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32
> pip -V
pip 22.2.2 (python 3.9)
> conda activate bammer

(bammer) > python -V
Python 3.6.13 :: Anaconda, Inc.
(bammer) > pip -V
pip 21.2.2 (python 3.6)
(bammer) > python
>>> import cv2
>>> import torch
>>> cv2.__version__
'4.5.3'
>>> torch.__version__
'1.10.2'
```

- Pytorch Platform

  * CUDA 11.6

    ```
    conda install pytorch torchvision torchaudio pytorch-cuda=11.6 -c pytorch -c nvidia
    ```

  * CPU
  
    ```
    conda install pytorch torchvision cpuonly -c pytorch
    ```

- Google Colab

Mount [Google Drive](https://drive.google.com/) on [Google Colab](https://colab.research.google.com/) and use it. Python and [OpenCV](https://opencv.org/) versions are below:

```python
>>> import sys
>>> print(sys.version)

3.8.10 (default, Nov 14 2022, 12:59:47) 
[GCC 9.4.0]

>>> import cv2
>>> print(cv2.__version__)

4.6.0
```
