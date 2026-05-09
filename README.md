# Speech-Emotion-Recognition-System
This project implements a gender-aware emotion recognition system that classifies speech into 10 categories: male/female variants of calm, happy, sad, angry, and fearful emotions. Built with TensorFlow/Keras and Librosa for audio processing.

**Dataset:** 
[RAVDESS](https://zenodo.org/records/1188976). 7356 files (total size: 24.8 GB). The dataset contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression.

**Solution:**
Since, we decipher the emotion behind a certain voice, this is a classic classification problem. Convolution Neural Network would be the ideal choice for this scenario. Multilayer perceptrons and Long Short Term Memory models were also tried upon but they under-performed with very low accuracies.

**Performance:** 72.73% accuracy on test data
