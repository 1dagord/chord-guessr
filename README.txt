Chord Guessr

This project involves three major components:
1) Data Acquisition
2) Feature Extraction
3) Machine Learning Model Evaluation

First, the song names in the Billboard Top 100 All Time list are fed into YouTube and each song is downloaded, then converted into a .mp3 file for ease of use.

Then, FFT analysis is performed on a random sample of the songs to identify which chord tones are most likely to predict the key of an entire song. Since nearly all of these songs are contemporary and are composed as such, key changes are not uncommon. The feature extraction step accomodates this fact.

Finally, a machine learning model will be evaluated on the remaining subset of songs and scored based on its accuracy.


Development plan leading up to CG:
1) create NN to guess key of song
2) transpose song down to C


Development Plan for Chord Guessr:
(_) Produce dataset of major, minor, and dominant chords *USE ONE KEY, TRANSPOSE TEST DATA DOWN TO KEY*
	1a) Choose five different timbres of same instruments (guitar, piano, something brass, something woodwind)
	1b) Create set of major, minor, and dominant chords with combinations of 1 to 4 instruments with varying harmonic positions
(_) Train neural network to classify
