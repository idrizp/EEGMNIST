# EEGMNIST

Classifies an input EEG into a number from 1 to 9, based on what number the individual is thinking. 

The actual values will range from 0-10, where 0 indicates that they weren't thinking of a number.


The model architecture works by taking the spectrograms of EEGs and inserting them as grayscale "images" into a CNN, that then maps these spectrograms from 0 to 10. 

Relatively simple, but quite fun to see working.

The data used is from [MindBigData's EEG dataset.](https://mindbigdata.com/opendb/index.html)