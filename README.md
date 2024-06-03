# Emotive   
### Emotion Recognition in Speech   
#### Sike Ogieva, Kien Tran, Bach Le and Suaryanshu Khanal

The aim of this project is to build and train neural networks to recognise the emotion in human speech. 

#### Data
We will be using the audio-speech subset of the Ryaerson Audio-Visual Database of Emotional Speech and Song. The dataset comprises WAVfiles, with each one of 24 actors contributing 60 recordings, totaling 1,440 files. There are equal numbers of male and and female actors (12 each). The men are assigned odd number actor ids and the women even numbers. 
Every actor delivers their lines in a level North American accent. Files are identified by emotion (neutral, calm, happy, sad, angry, fearful, disgusted and surprised); emotional intensity (normal and strong), the text of their statement, and the speaking actor. Neutral emotions have no intensity.

#### Data Quality
This is a carefully curated dataset, with data points generally well distributed amongst our target variables (eight different emotions). The exception is the neutral emotion which only has entries for a normal intensity, while the other labels have data for both normal and strong intensities. This is a reasonable property.
Additionally, the other features (the gender of the speaker, the statement being spoken, the speech intensity, and the speaking individual of which there twenty four persons) were perfectly distributed within the larger dataset and also within each target variable.  
Having dealt with the dataset distribution, we use spectograms and wave plots to show that there are enough differences in audio such as frequency, amplitude, troughs and crests etc, across different labels such that a good model can find features to differentiate on. 
