Tensorflow 1.6 for Jetson TX2.
Pre-built wheel files for installing TensorFlow 1.6 on Jetson TX2.

# Installation

## Get wheel files

For now it is only built for Jetson TX2

```bash
git clone https://github.com/openzeka/Tensorflow-for-Jetson-TX2.git
```

## Jetpack 3.1

* Python 2.7

```bash
cd Tensorflow-for-Jetson-TX2/Jetpack-3.1/1.6
sudo pip install tensorflow-1.6.0rc1-cp27-cp27mu-linux_aarch64.whl
```

## Jetpack 3.2

* Python 2.7

```
cd Tensorflow-for-Jetson-TX2/Jetpack-3.2/1.6
sudo pip2 install tensorflow-1.6.0rc1-cp27-cp27mu-linux_aarch64.whl
```

* Python 3.5

```
cd Tensorflow-for-Jetson-TX2/Jetpack-3.2/1.6
sudo pip3 install tensorflow-1.6.0rc1-cp35-cp35m-linux_aarch64.whl
```


# Build environment

If you install Jetpack 3.1

 - Jetpack 3.1
 - CUDA 8.0 
 - cuDNN 6.0.21 

If you install Jetpack 3.2

 - Jetpack 3.2
 - CUDA 9.0
 - cuDNN 7.0.05
