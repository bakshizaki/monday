---
layout: post
title:  "Assignment Writer"
description: Hobby Project Designed to Copy text and write in personalized handwriting.
img: initial.png
date: 2017-03-07  +0200
---

# Assignment-Writer
A hobby project in progress which started with the idea of capturing handwriting of a person using a smartphone, make it a font and use it to write any given text using an embedded hardware. Inspired from a friend's idea who wanted a machine which could write his school assignments for him.  

To capture handwriting, a picture of the handwritten alphabets is taken and processed using OpenCV which detects individual alphabets and generates data which can be sent to the hardware to write a particular letter.  
Original Image:  
![original](https://github.com/bakshizaki/monday/blob/gh-pages/assets/img/alphabets2.jpg?raw=true)  
Screenshots  
![initial](https://github.com/bakshizaki/monday/blob/gh-pages/assets/img/initial.png?raw=true)     ![final](https://github.com/bakshizaki/monday/blob/gh-pages/assets/img/final.png?raw=true)  

The application also includes a character recognition activity which utilizes Tesseract OCR engine for character recognition. The generated output can be later used as input text to write in custom font.  
![ocr1](https://github.com/bakshizaki/monday/blob/gh-pages/assets/img/ocr1.png?raw=true)       ![ocr2](https://github.com/bakshizaki/monday/blob/gh-pages/assets/img/ocr2.png?raw=true)  

### Building: 
For building the project, you would need to add these libraries.  
1) OpenCV4Android Library OpenCV-2.4.11- android -sdk which is available at  
https://sourceforge.net/projects/opencvlibrary/files/opencv-android/  
2) Tesseract OCR Engine for Android available at  
https://github.com/rmtheis/tess-two  
3) CropImage library by Lorenzo Villani available at  
https://github.com/lvillani/android-cropimage   