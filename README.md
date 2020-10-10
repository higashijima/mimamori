# mimamori
ツクレル教材見守りカメラ

## 先にインストールするもの
```
# OSのアップデート
sudo apt update -y
# TensorFlowのインストール
# 関連ライブラリ 
sudo apt install -y libhdf5-dev \
                 libc-ares-dev \
                 libeigen3-dev \
                 openmpi-bin \
                 libatlas-base-dev

pip3 install --no-deps keras_applications==1.0.8 keras_preprocessing==1.1.0
pip3 install h5py==2.9.0 grpcio==1.25.0

# TensorFlow
wget https://isaax-public.s3-ap-northeast-1.amazonaws.com/ai-kit/tensorflow-2.0.0-cp37-cp37m-linux_armv7l.whl
pip3 install --user tensorflow-2.0.0-cp37-cp37m-linux_armv7l.whl

# OpenCVのインストール
# 関連ライブラリ
sudo apt install libjasper1 \
                 libqtcore4 \
                 libqtgui4 \
                 libqt4-test
# OpenCV
pip3 install opencv-python==3.4.6.27

# imutilsのインストール
pip3 install imutils
```

