# Data Preparation (Visualization and Setup)
---------------------------------------------------------------------------------------------------
## Vision / UCID Dataset
The aim of the UCID is to provide a benchmark dataset for image retrieval. The database has over 1300 images together with a ground truth (predefined query images with corresponding model images that should be retrieved). It is envisaged that the dataset is used for the evaluation of image retrieval techniques.
Link: https://qualinet.github.io/databases/image/uncompressed_colour_image_database_ucid/

---------------------------------------------------------------------------------------------------
## Dresden / FAU
## DSO-I
## Korus
## NC2017
## MFC2018
## MFC2019

---------------------------------------------------------------------------------------------------
# The Deutsche Welle Image Forensics Dataset
The Deutsche Welle Image Forensics Dataset is a small but highly structured dataset of forged images. It contains six base images, all created by Ruben Bouwmeester: two are captured with a semi-professional DSLR camera, two are captured using a smartphone and two are downloaded from the DW Innovation Flickr account.
Link: https://revealproject.eu/the-deutsche-welle-image-forensics-dataset/

# Columbia Uncompressed Image Splicing Detection Evaluation Dataset
Images are in high resolution and uncompressed, removing further the compression concern. Also, the EXIF information is retained, therefore this set is not restricted to splicing detection but also suitable for other computer vision algorithms since the ground truth of exposure settings are accessible. Please feel free to download and test your algorithm on it.
Link: https://www.ee.columbia.edu/ln/dvmm/downloads/authsplcuncmp/

# Columbia Image Splicing Detection Evaluation Dataset
A  data set of 1845 image blocks with a fixed size of 128 pixels x 128 pixels. The image blocks are extracted from images in the CalPhotos collection, with a small number of additional images captured by digital cameras. The dataset includes about the same number of authentic and spliced image blocks, which are further divided into different subcategories (smooth vs. textured, arbitrary object boundary vs. straight boundary).
Link: https://www.ee.columbia.edu/ln/dvmm/downloads/AuthSplicedDataSet/AuthSplicedDataSet.htm

# FIDAC- FORGED IMAGES DETECTION AND CLASSIFICATION
This dataset consists of 2 types of images i.e Authentic and Tampered. There are a total of 1,389 Authentic images and 597 Tampered images. Authentic images are camera clicked images in raw form & tampered images are the one being edited by Adobe Photoshop and few mobile applications. Different types of forgery techniques like copy-move, splicing, color enhancement, resizing etc have been applied on the tampered images.
Link: https://ieee-dataport.org/documents/fidac-forged-images-detection-and-classification

# CoMoFoD - Image Database for Copy-Move Forgery Detection
CoMoFoD database for a copy-move forgery detection consist of 260 forged image sets in two categories (small 512x512, and large 3000x2000). Images are grouped in 5 groups according to applied manipulation: translation, rotation, scaling, combination and distortion. Different types of postprocessing methods, such as JPEG compression, blurring, noise adding, color reduction etc., are applied to all forged and original images.
Link: https://www.vcl.fer.hr/comofod/

# FORGERY IMAGE DATASET
The dataset consists of 1000 original and 3000 forgery images generated from the original images. The original images have been retrieved from publicly available repositories. Three different models have been used for creating the forgery images: cut-paste, copy-move, and erase-filling. Both pre-processing (sharpening, color enhancement, resizing, blurring, regulating exposure) and post-processing (sampling, rotation, masking) techniques have been considered for the generation of the forgery images. The dataset can be used for research in the area of fake image identification. This dataset has been created in the context of the H2020 project SocialTruth.
Link: https://ieee-dataport.org/documents/forgery-image-dataset#files

# Image Manipulation Dataset
It includes 48 base images, separate snippets from these images, and a software framework for creating ground truth data. The idea is to "replay" copy-move forgeries by copying, scaling and rotating semantically meaningful image regions. Additionally, Gaussian noise and JPEG compression artifacts can be added, both on the snippets and on the final tampered images. As a consequence, this dataset can also be used to apply other algorithms than copy-move forgery detection, but also algorithms for the detection of resampling and double-JPEG compression.
Link: https://www5.cs.fau.de/research/data/image-manipulation/

# Copy-Move Forgery Dataset
The Dataset is made of medium sized images (almost all 1000×700 or 700×1000) and it is subdivided into several datasets (D0, D1, D2). The first dataset D0 is made of 50 not compressed images with simply translated copies. For the other two groups of images (D1, D2) we selected 20 not compressed images, representing simple scenes (single object, simple background), rather than complex scenes, as we are interested in studying primarily the robustness against some specific attacks. 
Link: http://www.diid.unipa.it/cvip/?page_id=48

# The PS-Battles Dataset - an Image Collection for Image Manipulation Detection
The PS-Battles dataset which is gathered from a large community of image manipulation enthusiasts and provides a basis for media derivation and manipulation detection in the visual domain. The dataset consists of 102'028 images grouped into 11'142 subsets, each containing the original image as well as a varying number of manipulated derivatives.https://github.com/dbisUnibas/PS-Battles

# CG-1050: Original and tampered images (Color and grayscale)
This dataset is composed of 100 natural images, 1050 tampered counterparts, and 1380 masks.  For every image were applied from 10 to 11 manipulations among copy-move, cut-paste, colorizing and retouching operations. The dataset is organized into four directories: Original images, Tampered images, Mask images, and a Description file.
Link: https://data.mendeley.com/datasets/dk84bmnyw9/2

# Copy-Move Forgery Detection and Localization
## MICC-F220: this dataset is composed by 220 images; 110 are tampered and 110 originals.
## MICC-F2000: this dataset is composed by 2000 images; 700 are tampered and 1300 originals.
## MICC-F8multi: 8 tampered images with realistic multiple cloning.
## MICC-F600: this dataset is composed by 440 original images, 160 tampered images and 160 ground truth images
Link: http://lci.micc.unifi.it/labd/2015/01/copy-move-forgery-detection-and-localization/


# Coverage
COVERAGE contains copymove forged (CMFD) images and their originals with similar but genuine objects (SGOs). COVERAGE is designed to highlight and address tamper detection ambiguity of popular methods, caused by self-similarity within natural images.
Link: https://github.com/wenbihan/coverage

---------------------------------------------------------------------------------------------------

# Tampered Video Dataset
The Dataset includes 160 tampered videos, from 6 different original videos. Tampered videos are made selecting an object in a frame of a video, and tracking the object for a certain number of frames. The copied object is cloned into another part of the same video, after possible transformations. The dataset includes:
The 6 original videos.
The 160 tampered videos, divided per original video and subdivided per type of transformation.
For each tampered video we included also two Matlab files which report information about the tracking and the cloning process 
Link: http://www.diid.unipa.it/cvip/?page_id=48


# Manipulation-Detection
Link: https://github.com/Maikuki/Manipulation-Detection#manipulation-detection

# Forensics datasets
https://phdtopic.com/dataset/forensics/

# Video datasets
https://lesc.dinfo.unifi.it/en/datasets
https://www.salvationdata.com/downloads/

# Video Tampering Dataset
The Video Tampering Dataset (VTD) comprises a total of 33 videos, divided among three categories in video tampering: 1) Copy-Move, 2) Splicing, and 3) Swapping-Frames. Compared to existing datasets, this is a higher number of tampered videos, and with longer durations. The duration of every video is 16 seconds, with a 1280x720 resolution, and a frame rate of 30 frames per second. Moreover, all videos possess the same formatting quality (720pHD.avi). Both temporal and spatial video features were considered carefully during selection of the videos, and there exists complete information related to the doctored regions in every modified video in the VTD dataset.
Link: https://www.youtube.com/channel/UCZuuu-iyZvPptbIUHT9tMrA

# Video: Copy-move forgeries dataset
This dataset is composed by 20 video sequences used in [1]: 10 original and 10 forged ones. Each sequence has a resolution of 320x240 pixels, and a frame-rate of 30 fps. Original sequences have been recorded using low-end devices, thus they have all been compressed at the origin (using either MJPEG or H264 codecs). Forged sequences have been saved as uncompressed file (RV24, 24 bit RGB). In order to uniform all the sequences to the same standard, they have all been converted to uncompressed YUV (4:2:0) files. Notice that some of the original sequences come from the Surrey University Library for Forensic Analysis (SULFA) database [2]. Each forged sequence is supplied with an additional MAT file, which contains the differences of the Y, U, and V components for each frame of the original and the forged sequence. This serves as the ground truth.
Link: https://sites.google.com/site/rewindpolimi/downloads/datasets/video-copy-move-forgeries-dataset?tmpl=%2Fsystem%2Fapp%2Ftemplates%2Fprint%2F&showPrintDialog=1

# Photos Videos Manipulations Dataset
The dataset obtained by extracting a set of simple features from genuine and manipulated photos and videos, which are part of state-of-the-art existing datasets. The resulting dataset is balanced, and each entry comprises a label and a vector of numeric values corresponding to the features extracted through a Discrete Fourier Transform (DFT). The dataset is available in a GitHub repository, and the total amount of photos and video frames is 40,588 and 12,400, respectively
Link: https://github.com/saraferreirascf/Photos-Videos-Manipulations-Dataset

---------------------------------------------------------------------------------------------------
# Codes
## Copy Move Forgery Detection(DBSCAN Clustering)
https://www.kaggle.com/code/himj26/copy-move-forgery-detection-dbscan-clustering

## Project image forgery
https://www.kaggle.com/code/alimistro123/project-image-forgery

## Forgery Detection by using extracted ELA features
https://www.kaggle.com/code/masouduut94/forgery-detection-by-using-extracted-ela-features

## Image Forgery Detection --2
https://www.kaggle.com/code/anjumariaraju/image-forgery-detection-2

## GANs form Scratch to Advanced
https://www.kaggle.com/code/muhammedfathi/gans-form-scratch-to-advanced

## Project image forgery ELA 18.5.2022
https://www.kaggle.com/code/ibrahemnezar/project-image-forgery-ela-18-5-2022

## Image forgery detection using CNN (casia dataset)
https://www.kaggle.com/code/shubhamkadam99/image-forgery-detection-using-cnn-casia-dataset/

## Image forgery apply 3 Level DWT
https://www.kaggle.com/code/alimistro123/image-forgery-apply-3-level-dwt

## ManTraNet
https://github.com/ISICV/ManTraNet
