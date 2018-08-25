# drum_bassline_dataset
A dataset of audio drum loops with accompanying basslines for two styles of music (House and Soca). These two datasets were used for training the following model:

https://github.com/behzadhaki/bassline_seq2seq


# Description of Files:

1. For each Style (House/Soca), 50 samples are available. Each sample drum loop along with bassline is located in a separated subfolder (The folder titles correspond to Discogs release ids). 

2. In each release folder, there are 3 folders: A. harmonic, B. percussive, and C. percussive_monoloaded
3. The "harmonic" folder contains the transcription of a bassline. The transcription is provided as a text file and a midi file. Note that the midi file isn't as accurate as the text file as the notes in the midi files have equal duration.
4. The "percussive folder, contains a drum loop which has been loaded using an equal loudness filters. Moreover, this folder contains a symbolic representation which is based on time quantized onsets in 8 different frequency bands. The duration of the drum loops are not matched in the dataset. They need to be either cut short or be concatenated to match the length of the basslines.
5. The "percussive_monoloded" folder contains the same drum loop but loaded without any processing. (UPDATE: Missing for some House samples)


