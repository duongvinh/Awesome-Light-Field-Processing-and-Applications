# Awesome-Light-Field-Processing-and-Applications
A up-to-date of awesome light field processing and applications, inspired by [awesome-php](https://github.com/ziadoz/awesome-php).
## Contributing
Please feel free to send me [pull requests](https://github.com/Vinh-Duong/Awesome-Light-Field-Processing-and-Applications/pulls) or email (duongvinhyd@gmail.com) to add links.

## Table of Contents

 - [Overview Light Field: Tutorial and Talks](#courses)
 - [Light Field Compression](#courses)
 - [Light Field Depth Estimation](#papers)
 - [Light Field Super-Resolutions](#software)
 - [Light Field Denosing](#tutorials-and-talks)
 - [Light Field Quality Assessment](#resources-for-students)
 - [Research Groups](#blogs)
 - [Useful Links](#links)
 
 ## Overview Light Field: Tutorial and Talks

### Early papers
* [Light Field Rendering](https://graphics.stanford.edu/papers/light/light-lores-corrected.pdf)
* [Light fields and computational imaging](https://graphics.stanford.edu/papers/lfphoto/levoy-lfphoto-ieee06.pdf)
* [The lumigraph](https://cseweb.ucsd.edu/~ravir/6160-fall04/papers/p43-gortler.pdf)
* [Light Field Photography with a Hand-held Plenoptic Camera](https://cseweb.ucsd.edu/~ravir/6160-fall04/papers/p43-gortler.pdf)
* [The focused plenoptic camera](http://www.tgeorgiev.net/EG10/Focused.pdf)


### Overview Light Field Papers
* [Light Field Image Processing: An Overview](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8022901)
* [Computational photography with plenoptic camera and light field capture: tutorial](https://www.osapublishing.org/josaa/abstract.cfm?uri=josaa-32-11-2021)


### Lectures, Tutorial and Talks
* [Dynamically Reparameterized Light Fields & Fourier Slice Photography](https://people.mpi-inf.mpg.de/~theobalt/courses/Barth_Refocussing.pdf)
* [Introduction to the Light-Field Camera](http://disp.ee.ntu.edu.tw/class/20131129-LightField_intro.pdf)
* [Computational Methods for Radiance](http://www.tgeorgiev.net/WSCG2010/Computation.pdf)
* [Computational Plenoptic Imaging](https://web.media.mit.edu/~gordonw/courses/ComputationalPlenopticImaging/CPICourseNotes.pdf)
* [Plenoptic Imaging Representation](http://www.eusipco2015.org/files/EUSIPCO2015_TUTO2/index.pdf)
* [Light-Field Cameras](http://www.cs.cmu.edu/afs/cs/academic/class/15869-f11/www/lectures/18_lfcamera.pdf)
* [Light Field Photography](https://web.stanford.edu/class/ee367/slides/lecture8.pdf)
* [CVPR Tutorial Camera Culture Light Fields](http://tab.computer.org/pamitc/archive/cvpr2009/raskarCVPRlightfieldIntroFinal.pdf)


## Light Field Image/Video Coding

### A List of Survey Paper Light Field Image Compression
* [Dense Light Field Coding: A Survey](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9020136)
* [Lenslet Light Field Image Coding: Classifying, Reviewing and Evaluating](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9016088)
* [The JPEG Pleno Light Field Coding Standard 4D-Transform Mode: How to Design an Efficient 4D-Native Codec](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9200599)


### Light Field Image Compression
#### Non-learning based
* [Compression of unfocused plenoptic images using a displacement intra prediction](https://ieeexplore.ieee.org/document/7574673) 
* [Hevc-based light field image coding with bi-predicted self-similarity compensation](https://ieeexplore.ieee.org/document/7574667) 
* [Image reshaping for efficient compression of plenoptic content](https://ieeexplore.ieee.org/document/8012378) 
* [Image reshaping for efficient compression of plenoptic content](https://ieeexplore.ieee.org/document/8022889) 
* [Light field image coding using high order intra block prediction](https://ieeexplore.ieee.org/abstract/document/7961268/) 
* [Locally linear embedding-based prediction for 3D holoscopic image coding using HEVC](https://ieeexplore.ieee.org/document/6951961) 
* [Pseudo-sequence-based 2-d hierarchical coding structure for light-field image compression](https://ieeexplore.ieee.org/document/7972959) 
* [Pseudo-sequence-based light field image compression](https://ieeexplore.ieee.org/document/7574674) 
* [Rate-distortion optimized super-ray merging for light field compression](https://ieeexplore.ieee.org/document/8553485)
#### Learning based
* [Learned Focused Plenoptic Image Compression with Microimage Preprocessing and Global Attention](https://arxiv.org/abs/2305.00489)
* 
### Light Field Video Compression
#### Intra-coding tools
* [Imaging-Correlated Intra Prediction for Plenoptic 2.0 Video Coding](https://ieeexplore.ieee.org/document/9102725)
* [Plenoptic 2.0 Intra Coding Using Imaging Principle](https://ieeexplore.ieee.org/document/9528842)
* [Pixel Gradient Based Zooming Method for Plenoptic Intra Prediction](https://ieeexplore.ieee.org/document/9675380)
* [Zoomable Intra Prediction for Multi-Focus Plenoptic 2.0 Video Coding](https://ieeexplore.ieee.org/document/9506363)
* 
#### Inter-coding tools
* [Macropixel based Fast Motion Estimation for Plenoptic Video Compression](https://link.springer.com/chapter/10.1007/978-3-030-00764-5_67)
* [FAST and Efficient Microlens-Based Motion Search for Plenoptic Video Coding](https://ieeexplore.ieee.org/document/9506117)
* [Microimage-based Two-step Search For Plenoptic 2.0 Video Coding](https://ieeexplore.ieee.org/abstract/document/10219886)
* [MCPNS: A Macropixel Collocated Positionand Its Neighbors Search for Plenoptic 2.0 Video Coding](https://arxiv.org/abs/2310.08006)
* [Ray-Space Motion Compensation for Lenslet Plenoptic Video Coding](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10044591)



##  Light Field Depth Estimation
### A List of Survey Paper Light Field Image Compression
* [A axonomy and evaluation of dense light field depth estimation algorithms](http://lightfield-analysis.net/benchmark/paper/survey_cvprw_lf4cv_2017.pdf)

### Non-Learning Based Methods
* [Oclusion-aware depth estimation using light-field cameras](https://cseweb.ucsd.edu/~ravir/lfocclusion.pdf)
* [Occlusion-model guided antiocclusion depth estimation in light field](https://ieeexplore.ieee.org/document/7987707)
* [Accurate light field depth estimation with superpixel regularization over partially occluded regions](https://ieeexplore.ieee.org/document/8362692)
* [Robust light field depth estimation using occlusion-noise aware data costs](https://ieeexplore.ieee.org/abstract/document/8022875)
* [Robust depth estimation for light field via spinning parallelogram operator](https://www.sciencedirect.com/science/article/pii/S1077314215002714)

### Deep-Learning Based Methods
* [EPINET: A Fully-Convolutional Neural Network using Epipolar Geometry for Depth from Light Field Images](https://arxiv.org/pdf/1804.02379.pdf)








