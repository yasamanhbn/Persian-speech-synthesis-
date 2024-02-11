# Fine-Tuning SpeechT5 for Persian Text-to-Speech

This repository contains a notebook that demonstrates how to fine-tune the SpeechT5 model from Transformers on the text-to-speech task for the Persian language.

The unique aspect of SpeechT5 is that the model is pre-trained on a combination of speech-to-text and text-to-speech data, allowing it to learn a unified space of hidden representations shared by both text and speech. This enables us to fine-tune the same pre-trained model on different tasks.

In this notebook, we will begin with an existing fine-tuned TTS model that was originally trained on English speech, and fine-tune it for the Persian language using the Common Voice dataset.

This TTS model will also support multiple speakers through x-vector speaker embeddings.

ine-tune the SpeechT5 model for Persian text-to-speech, follow the steps outlined in the notebook. This includes loading the pre-trained model, preparing the dataset, and executing the fine-tuning process.
