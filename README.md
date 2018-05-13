# ImageDistortion
This is a demo that restores distorted images based on the distortion equation.

## Mathematical theory
<div align=center>  
  
![](https://github.com/TianQi-777/ImageDistortion/blob/master/Images/distort.jpg)
</div>

## Additional Prerequisites for this project
**OpenCV**  
Use [OpenCV](http://opencv.org) to process images.

## Build and Run
```
cd XX/XX(include undistort_Image.cpp ,test.png and CMakeLists.txt)  
mkdir build  
cd build  
cmake ..  
make -j2  
./undistort_image
```

## Result
**Distort**  
<div align=center>  
  
![](https://github.com/TianQi-777/ImageDistortion/blob/master/Images/distort_.png)
</div>

**Undistort**  
<div align=center>  
  
![](https://github.com/TianQi-777/ImageDistortion/blob/master/Images/undistorted.png)
</div>
