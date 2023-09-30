# Speech-Emotion-Recognition

Speech Emotion Recognition (SER) is a system that can identify the emotion of different audio samples. From the description, this task is similar to text sentiment analysis, and both also share some applications since they differ only in the modality of the data – text versus audio. Like sentiment analysis, you can use speech emotion recognition to find the emotional range or sentimental value in various audio recordings such as job interviews, caller-agent calls, streaming videos, and songs. 

From a machine learning perspective, speech emotion recognition is a classification problem where an input sample (audio) needs to be classified into a few predefined emotions. Of course, the challenge in this problem goes beyond technical – how does one even define emotion and consistently decide the class given an audio sample that can be ambiguous to even humans?

The issue is more pressing for dataset creators, but it also becomes essential while evaluating a trained model. Further below, we will see that our dataset contains two similar-sounding emotions, “calm” and “neutral,” which can be tricky for even humans to ascertain in ambiguous cases. Meanwhile, “angry” and “happy” have prominent differences that the model can quickly learn.

So, it is clear that machine learning models need to delve deeper into the feature extraction and non-linearity of the audio signals to effectively capture the nuanced differences in speech that humans can detect intuitively. Currently, researchers work with audio signals by treating them either as time-series data or using spectrograms to generate numeric and image forms of the audio. All these techniques involve some or the other kind of transformation to the original data, thus making feature loss likely. There is still a need to make machine learning models robust at learning features from audio data – robustness in classification or generation tasks will follow.

For dataset, refer: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio
                    https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess
                    https://www.kaggle.com/datasets/ejlok1/cremad
                    https://www.kaggle.com/datasets/ejlok1/surrey-audiovisual-expressed-emotion-savee
