# Your-Voice-Your-Device-Your-Language-Challenge

This notebook serves as a starter guide for audio transcription using the SeamlessM4T model, specifically tailored for the Sartify ITU Zindi Test Dataset. It demonstrates how to process audio files, perform automatic speech recognition (ASR) in Swahili ("swh").

# The notebook includes:

- Installation of required libraries (fairseq2, pydub, sentencepiece, and seamless_communication).
- Loading and preprocessing audio data from the dataset.
- Utilizing the SeamlessM4T medium model with the vocoder_36langs for transcription.
- Batch processing of audio files to optimize performance.
- Post-processing of predictions to create a submission-ready CSV file.
