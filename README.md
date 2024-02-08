## Code for Automatic Movie Tag Generation System

### common
- dataset would be located: ~/dataset/[here]


### test 1) genere classification 

* dataset consists of 933 movie trailer video files  
    - [Dropbox Link : spectrogram image files for extracted audio from trailer](https://www.dropbox.com/scl/fi/d23sb6d8u10nppyy8qk3e/Classification_Merge.zip?rlkey=zru2fo8lv5tr244d679mr0le7&dl=0)
- 6 genres : Action, Comedy, Crime, Drama, Horror, Romance
- run code: ~/code/[filename].ipynb


### test 2) genre classification

* test.csv file include 100 audios with 7 major feature values(chroma_stft, rms, spectral_centroid, spectral_bandwidth, spectral_rolloff, zcr, mfcc) 
and 10 extracted tags(idx) from musicnn models
* train with random forest model then evaluate
- run code in google colab: movie100Audio_genre_classification.ipynb


### Module 3) tag 