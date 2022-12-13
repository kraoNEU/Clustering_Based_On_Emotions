# &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp; &nbsp;Clustering Based on Emotions

Chelamkuri Venkata Krishna Rao, Nukala Siva Akhil Kumar Reddy

chelamkuri.v@northeastern.edu | nukala.si@northeastern.edu

Abstract

Emotional Based Clustering or EBC for short, is a way of converting the audio file each of which contains an emotion such as happy, anger, sad, disgust, fear into a matrix array through feature engineering techniques backed by methods such as Zero Crossing Rate, Chroma Shift, MFCC (Mel Frequency Cepstral Coefficients) and treating the Audio components as an Image to our Models and employing un-supervised learning methodologies to cluster the emotions is the motive of our project.

Introduction

O  ur project, which is clustering based on emotions, has been developed using various techniques such as KMeans, GMM, BIRCH, PCA, AutoEncoders. The datasets contain Audio Files that are in .wav format which were collected from various open-source datasets such as: CREMA-D (Crowd-Sourced Emotional Multimodal Actors Dataset), SAVEE (Surrey Audio-Visual Expressed Emotions), TESS (Toronto Emotional Speech Set) all these datasets are pub-licly available. These Datasets were then converted to a 1-D array (while using Zero crossing Rate, Chroma Shift, Spec-trograph) or into a 3-D array matrix representation while using MFCC. The feature engineering techniques using various versions of the Fourier Transformation.


The Input dataset which is audio files are based on 3 components: Amplitude, Frequency and Time. The challenge here is that we cannot input the audio files directly. The Feature Engineering part of the dataset is where we trans-form the 3-component waveform that constitutes an audio file into a 1-D array and a 3-D array. These features capture the frequency and the waveform characteristics of the dataset.

Using all these techniques to decompose and transform the waveform and to reduce it to lower dimension led to a lot of background understanding of the Fourier Transform and Short Fourier transform in case of Spectrograph.

The Intention of our project is to treat the audio file like an array or a 3-dimentional array of varying amplitude, frequency, and time characteristics and to clusters those individual unique emotional labels to the clusters and identify them based on the Image characteristics based on previous learned imaging data to correctly identify the clusters of emotions.
