### Automatic-Speech-Recognition-in-WOLOF

- This notebook is part of my participation in this [Zindi competition](https://zindi.africa/competitions/ai4d-baamtu-datamation-automatic-speech-recognition-in-wolof) about Automatic Speech Recognition in WOLOF.

- [My Zindi Profile](https://zindi.africa/users/data_scientist)
- The main goal is to build an ASR model for the WOLOF language
- Fine-tuned the ```facebook/wav2vec2-large-xlsr-53``` model from ```Hugging Face``` Model Hub
- Used ```datasets``` from the ```transformers``` library to preprocess the transcriptions and ```torchaudio``` to resample the audio files to 16 kHz
- Model hyperparameters:  ```attention_dropout=0.05,
    hidden_dropout=0.05,
    feat_proj_dropout=0.0,
    mask_time_prob=0.05,
    layerdrop=0.1,learning_rate=1e-4```
- The ```Automatic_Speech_Recognition_in_WOLOF.ipynb``` notebook contains the step for training and submitting your model
