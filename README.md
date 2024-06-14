# Panorama Stitching

### Requirements

1. NumPy
2. Matplotlib
3. OpenCV

### Implementation 

1. To stitch a given set of images, run the following: 
```
python3 Wrapper.py --InputPath <path_to_data> --Scale <scaling_images> 
```

Summary:

Stitches a given set of images with a procedural flow of: 
1. Feature Extraction using SIFT 
2. Feature Matching using Brute Force Matcher  
3. Homography Estimation
4. Image Warping and Blending

Saves the output of every procedure in the corresponding folders.

### Results


<!-- |1 | 2| 3|4 |5 |
|:-------:|:-------:|:-------:|
|![Images](/Phase1/Data/Set5/1.jpg)|![Images](/Phase1/Data/Set5/2.jpg) |![Images](/Phase1/Data/Set5/3.jpg) | ![Images](/Phase1/Data/Set5/4.jpg) | ![Images](/Phase1/Data/Set5/5.jpg) | -->

### Results

|1 | 2| 3|4 |5 |
|:-------:|:-------:|:-------:|:-------:|:-------:|
|<img src="/Phase1/Data/Set5/1.jpg" width="200">|<img src="/Phase1/Data/Set5/2.jpg" width="200">|<img src="/Phase1/Data/Set5/3.jpg" width="200">|<img src="/Phase1/Data/Set5/4.jpg" width="200">|<img src="/Phase1/Data/Set5/5.jpg" width="200">|