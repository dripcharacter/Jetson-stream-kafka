# Jetson-Nano-Initial-Setting-for-FFmpeg/OpenCV/kafka
## 1. Jetson-Nano-JetPack
First, you need to setup NVIDIA JetPack SDK (Jetson Nano Linux OS). please follow official document</br>
https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit</br>
This is optional, but useful for your Jetson Nano life</br>
I recommand you to install jetson-stats and lightdm (lightdm is for saving RAM for installing OpenCV)</br>
https://whiteknight3672.tistory.com/314?category=723167</br>

## 2. OpenCV
Secondly, in Jetson Nano, OpenCV have to install via cross compiling. So, it is hard to install OpenCV for python via `pip install opencv-python`. It will be easy to follow this guide to install OpenCV for python.</br>
https://github.com/Qengineering/Install-OpenCV-Jetson-Nano/tree/main</br>

## 3. FFmpeg
Third, in my case, I had to use hardware accelerated encoding. So, I installed old version with this guide.</br>
https://github.com/jocover/jetson-ffmpeg</br>
You have to use compiled binary to use hardware accelerated encoding/decoding