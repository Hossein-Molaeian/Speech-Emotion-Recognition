# Speech Emotion Recognition

This project focuses on enabling machines to understand human emotions from speech.

## Key Features:

- Identifies seven types of emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.
- Long Short-Term Memory (LSTM) layers for handling sequential data.
- MFCCs for capturing the phonetic properties of speech.
- Validation Accuracy: 67%

## Technologies Used

- **Python**: The primary language.
- **Keras with TensorFlow**: For building and training the neural network models.
- **Librosa**: For audio processing and feature extraction.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib and Seaborn**: For data visualization.

## Dataset Information

- **Source**: [Toronto Emotional Speech Set (TESS)](https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess)
- **Details**: 2800 audio samples in WAV format recorded at 22050 Hz. Each sample is up to 3 seconds long.

## Model

- 1 LSTM layer with 256 units
- 2 Dense layers with 128 and 64 units using ReLU activation
- Dropout layers with a rate of 20% after each Dense layer
- Output layer with 7 units using softmax activation
- **Optimizer**: Adam
- **Loss Function**: Categorical Cross-Entropy
- **Training Duration**: 50 epochs with a batch size of 64

##

**Thanks for visiting this project!**
