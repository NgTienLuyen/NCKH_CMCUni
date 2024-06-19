# Regional classification in speech 
1. CHUẨN BỊ MÔI TRƯỜNG VÀ THƯ VIỆN
!pip install paddlepaddle
import os
import librosa
import numpy as np
import cv2
import paddle
import paddle.nn as nn
import paddle.nn.functional as F
from paddle.io import Dataset, DataLoader, random_split
