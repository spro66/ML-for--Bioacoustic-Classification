# ML-for--Bioacoustic-Classification

This repository contains the various phases of code required to do the following:
 - Audio_cut: Cut the snippets of audio segments as per the begin and end time out of the detector
 - Spectrogram_Generation: Based on the segmented samples from the Audio cut, each 2 sec cut is converted into spectrogram for further processing
 - Call_Classification: Classification is done on the each sample of generated spectrogram to classify the call type in one of the given types - PantHoot(ph), Buttress(tb), Scream(sm), Any other type of sound (Other)
