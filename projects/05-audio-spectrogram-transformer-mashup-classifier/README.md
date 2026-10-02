# 05. Audio Genre Classification on Noisy Mashups

## Project Repository
`audio-spectrogram-transformer-mashup-classifier`

## Objective
Create a deep learning system for classifying music genres from noisy, synthetic mashup audio using spectrogram-based architectures and transformer-based audio modeling.

## Key Contributions
- Built synthetic audio generation pipeline with stem separation, beat synchronization, and noise injection
- Evaluated CRNN, ResNet-18, and Audio Spectrogram Transformer architectures
- Applied progressive curriculum training with augmentation, normalization, and label smoothing
- Tracked experiments using PyTorch Lightning and Weights & Biases

## Technical Stack
- PyTorch
- PyTorch Lightning
- Librosa
- Torchaudio
- Hugging Face Transformers
- Timm
- W&B

## Main Results
- Strong performance on noisy input signals with macro F1 in the 0.94-0.97 range
- Demonstrated robustness to environmental degradation and multi-track mixing conditions

## Key Learnings
- Noise augmentation is necessary for real-world resilience in audio classification
- Attention pooling across spectrogram crops yields better performance than simple uniform mean pooling

## Recruiter-Friendly Summary
This project demonstrates modern deep learning capability in audio processing, multimodal robustness, and transformer-based model training for complex real-world signal data.
