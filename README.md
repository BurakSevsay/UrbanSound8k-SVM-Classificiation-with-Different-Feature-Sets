# UrbanSound8k-SVM-Classificiation-with-Different-Feature-Sets

This is a lecture project (MMI-702, Machine Learning for Multimedia Informatics).

MFCC is one of the most popular feature extraction methods for audio classification. Also, SVM is one of the most popular traditional machine learning classifiers. The project aims to improve the machine learning model's performance by adding new features to the MFCC feature set.

Many experiments based on changing the feature set are done. Each feature set contains MFCC coefficients. In this project; harmonic to noise ratio, zero-cross rate, mean frequency, standard deviation of the signal (in terms of frequency), jitter and shimmer variants, spectral centroid are
combined with MFCC to observe the effect on the model performance.

As a result of the experiments, it is found that adding both harmonic to noise ratio (hnr) and zero-crossing ratio (zcr) is increased the performance.

Link for the Dataset: [UrbanSound8k](https://urbansounddataset.weebly.com/)

Some results: (Performance graphs for feature sets: 13 MFCC, 13 MFCC + harmonic-to-noise-ration + zero-crossing-rate, 32 MFCC + harmonic-to-noise-ration + zero-crossing-rate)

<img src="https://github.com/BurakSevsay/UrbanSound8k-SVM-Classificiation-with-Different-Feature-Sets/blob/main/Comparison_1.png" width="256" height="360">

<img src="https://github.com/BurakSevsay/UrbanSound8k-SVM-Classificiation-with-Different-Feature-Sets/blob/main/Comparison_2.png" width="256" height="360">
