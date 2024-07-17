# Speech Emotion Recognition

This project focuses on enabling machines to understand human emotions from speech.

### Key Features:

- **Emotion Detection**: Identifies seven types of emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.
- **Model Architecture**: Long Short-Term Memory (LSTM) layers for handling sequential data.
- **Feature Extraction**: MFCCs for capturing the phonetic properties of speech.
- **Accuracy**: 67% validation accuracy.

## Technologies Used

- **Python**: The primary programming language.
- **Keras with TensorFlow**: For building and training the neural network models.
- **Librosa**: For audio processing and feature extraction.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib and Seaborn**: For data visualization.

## Dataset Information

- **Source**: [Toronto Emotional Speech Set (TESS)](https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess)
- **Details**: 2800 audio samples in WAV format recorded at 22050 Hz. Each sample is up to 3 seconds long.

## How to Setup This Repository

You can follow these steps to run the project locally:

### 1. Clone this repository:

```bash
git clone https://github.com/Hossein-Molaeian/Speech-Emotion-Recognition.git
```

### 2. Install Required Libraries:

Make sure you have the necessary libraries installed. You can install them using pip:

```bash
pip install pandas numpy seaborn matplotlib librosa tensorflow keras
```

### 3. Prepare the Dataset:

Download the dataset from [here](https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess) and place it in the project directory.

### 4. Run the Project:

Open SER.ipynb file and run the cells sequentially to execute the project code and train the model.

##

**Thanks for visiting this project!**
