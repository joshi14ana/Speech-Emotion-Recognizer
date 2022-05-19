# Speech-Emotion-Recognizer
As humans, interacting with people through speech is one of the most natural ways to express ourselves. We rely so much on our emotions that we don’t even realise that for most humans non verbal cues such as pitch, loudness and rate of speech are efficient carriers of emotions. So, with increasing autonomous  technology, it is crucial for robots to understand human emotions such as to interact more effectively. 
Speech Emotion Recognition, abbreviated as SER, is a technology that extracts emotional features from speech signals by computer and contrasts and analyses the characteristic parameters and the emotional change acquired.
SER has entered so many areas these years, including:
The medical field: In the world of telemedicine the ability for a medical professional to discern what the patient is actually feeling can be useful in the healing process.
Customer service: In call center conversation may be used to analyze behavioral study of call attendants with the customers which helps to improve the quality of service.
Recommender systems: Can be useful to recommend products to customers based on their emotion towards that product.


# Dataset
The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) contains 7356 files (total size: 24.8 GB). 
The database contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. 
Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression. 
All conditions are available in three modality formats: Audio-only (16bit, 48kHz .wav), Audio-Video (720p H.264, AAC 48kHz, .mp4), and Video-only (no sound). 


# Results and Discussion
An MLPClassifier is used for this project. This is a Multi-layer Perceptron Classifier; it is a feedforward artificial neural network model that maps sets of input data onto a set of appropriate outputs.
The soundfile library as the name suggests, it can read and write sound files.
Librosa is a Python library for examining sound and music. It has a compliment bundle format, institutionalized interfaces, and names, in reverse similarity, measured capacities, and meaningful/readable code.
The model delivered an accuracy of 73.05% on 4 emotions using only few training samples.
