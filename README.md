# speech-emotion-recognition

* This projects aims to implement a model that will analyze a speech audio input, identify and classify the expressed emotion.
* It demosntrates the usages of CNNs on MFCC features, RNNs (LSTM) on MFCC and ZCR features and MobileNetV2 transfer learning on mel spectogram images.
* A concatenated model using all of the above models was also demonstrated with some success.
* A audio noise reduction Autoencoder using CNNs and Trasposed CNNs was also developed and shown to work to some degree.


## datasets links
* https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio
* https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess
* https://www.kaggle.com/datasets/ejlok1/cremad

## emotions reference notebooks
* https://www.kaggle.com/code/shivamburnwal/speech-emotion-recognition/notebook
* https://www.kaggle.com/code/gemmin/speech-emotion-recognition-90
* https://www.kaggle.com/code/yashtodwal/speech-emotion-recognition-using-lstm

## other notebooks references
* https://www.kaggle.com/code/doofensmirtz/85-validation-accuracy-tensorflow
* https://www.kaggle.com/code/karnikakapoor/music-generation-lstm
* https://github.com/jeffprosise/Deep-Learning/blob/master/Audio%20Classification%20(CNN).ipynb

## mel spectogram references
* https://towardsdatascience.com/deep-learning-for-classifying-audio-of-babies-crying-9a29e057f7ca
* https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53

## mfcc references
* https://medium.com/@derutycsl/intuitive-understanding-of-mfccs-836d36a1f779

## autoencoding references
* https://medium.com/analytics-vidhya/adding-noise-to-audio-clips-5d8cee24ccb8
* https://github.com/sleekEagle/audio_processing/blob/master/mix_noise.py
* https://github.com/christianversloot/machine-learning-articles/blob/main/creating-a-signal-noise-removal-autoencoder-with-keras.md
* https://github.com/christianversloot/keras-autoencoders/tree/master
  
## accuracy references
* https://saturncloud.io/blog/understanding-the-output-of-keras-categorical-accuracy-metrics/#:~:text=Categorical%20accuracy%20is%20a%20metric,labels%20are%20one%2Dhot%20encoded.
* https://towardsdatascience.com/keras-accuracy-metrics-8572eb479ec7
