# Rice Leaf Disease Detection

This is a web application built with Streamlit that uses deep learning to detect various diseases in rice plants from uploaded images.

## Features

- Upload images of rice leaves/plants
- Real-time disease detection
- Supports 14 different classifications including:
  - Bacterial Leaf Blight
  - Bakanae
  - Brown Spot
  - False Smut
  - Grassy Stunt Virus
  - Healthy
  - Leaf Blast
  - Leaf Scald
  - Leaf Smut
  - Narrow Brown
  - Ragged Stunt Virus
  - Sheath Blight
  - Sheath Rot
  - Tungro
- Displays prediction confidence scores

## Installation

1. Clone this repository
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Make sure you have the model file `rice_disease_classifier.h5` in the project directory

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```
2. Open your web browser and navigate to the displayed local URL
3. Upload an image of a rice plant using the file uploader
4. View the prediction results and confidence score

## Technical Details

- Built with Python 3.x
- Uses TensorFlow/Keras for the deep learning model
- Frontend built with Streamlit
- Model input size: 224x224 pixels
- Images are automatically preprocessed and normalized

## Requirements

See `requirements.txt` for a complete list of dependencies.

## License

This project is open source and available under the MIT License. 