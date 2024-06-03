# Emotive   
### Emotion Recognition in Speech   
#### Sike Ogieva, Kien Tran, Bach Le and Suaryanshu Khanal

The aim of this project was to build and train neural networks to recognise the emotion in human speech. 

We began by looking at previous literature to guide the building of our model. Then we analyze the RAVDESS for quality (both by ensuring that feature distribution is even, and that there are considerable audio-qualitative differences between files of different emotions). Then we augment our training files to increase them from 1_400 to 12_000 by adding noise, stretching, shifting and changing pitch. We selected the Mel Frequency Cepstral Coefficients as our features and extracted 40 of them per audio file. 

The models we built were k-Nearest Neighbors, Multilayer Perceptron,  Convolutional Neural Network, Long Short Term Memory Neural Network, Combined (CNN + LSTM)  Neural Network, and a Bidirectional LSTM Neural Network. Their performance was as follows.
