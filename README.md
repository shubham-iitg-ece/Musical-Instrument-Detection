# Musical-Instrument-Detection

### EE320 Digital Signal Processing Project

In this project, we present a system for classification of musical instruments belonging to different instrument families exploiting the various temporal and spectral features that characterize the "timbre" of a particular instrument. Many features covering both spectral and temporal properties and their influences on a musical sound was investigated, and their extraction algorithms were designed.The features were extracted from the dataset that consisted of 558 samples covering the full pitch ranges of 10 orchestral instruments from the string, brass and woodwind families. The classification results consolidated the dependence of an instrument's timbral uniqueness on the features, especially the spectral ones. The correct instrument family was recognized with ~96 % accuracy and individual instruments within the families with over 95 % accuracy for each of the three families considered. Also, a hierarchical classification framework is utilized keeping the mind the taxonomic nature of musical sounds. 

Project Webpage : [Musical Instrument Identification](https://k-priyadarshi.github.io/DSP-Project/)

### Block Diagram of Project:

![alt text](https://github.com/shubham-iitg-ece/Musical-Instrument-Detection/blob/master/block%20diagram.png "Musical Instrument Identification")

### Features used in individual classifiers:-

#### Basic classifier and brass classifier:-

1. Spectral centroid
2. Zero crossing
3. Spectral rollof
4. Spectral Crest
5. Spectral Decrease
6. Spectral Flatness
7. Spectral Skewness
8. Spectral Slope

#### String classifier:-

1. Spectral Centroid
2. Fundamental frequency
3. Spectral centroid variance
4. Spectral Crest
5. Spectral Decrease
6. Spectral Flatness
7. Spectral Skewness
8. Spectral Slope

#### Woodwind classifier :-

1. Spectral Centroid
2. Spectral Crest
3. Spectral Decrease
4. Spectral Flatness
5. Spectral Skewness
6. Spectral Slope
7. Fundamental Frequency
8. Variance of Spectral Centroid
9. MFCC

### Summary

As proposed in our approach, we were successfully able to build a two stage musical instrument detector. The various temporal and spectral features were successfully extracted using efficient algorithms, implemented in MATLAB. We were able to achieve decent test accuracy ( 96.42% for basic classifier, 100% for brass family , 96.7% for string family and 94.59% for the woodwind family). This shows that the features we had chosen for each of the classifiers based on the unique traits of each class were quite appropriate. We have also tried to ensure minimal use of inbuilt MATLAB functions and have written code to the features and supporting functions( like spectrogram, Radix 2 FFT,etc) too ourselves using the algorithms discussed in class (EE320- Digital Signal Processing). 
