## Overview
The Plant Disease Detection App allows users to upload an image of a plant leaf and receive a prediction of the disease affecting the plant. The app is built using Streamlit for the web interface and Keras for the deep learning model.

## Features
- Upload an image of a plant leaf
- Display the uploaded image
- Predict the disease affecting the plant
- Display the prediction result


## Installation
1. Clone the repository:
  
    git clone https://github.com/Thousiha/Plant_Disease_classsification
    cd Plant_Disease_classsification


2. Create a virtual environment:

    python -m venv venv
    ```

3. Activate the virtual environment:
    - On Windows:
 
      venv\Scripts\activate

    - On macOS and Linux:

      source venv/bin/activate
  

4. Install the required packages:

    pip install -r requirements.txt


5. Download the pre-trained model and place it in the root directory of the project. Ensure the model file is named `plant_disease_model.h5`.

## Usage
1. Run the Streamlit app:

    streamlit run app.py
  

2. Upload an image of a plant leaf using the file uploader in the web interface.

3. Click the 'Predict Disease' button to get the prediction.

## Model
The model used in this app is a pre-trained deep learning model capable of classifying diseases in plant leaves. The model can classify the following diseases:
- Tomato Bacterial Spot
- Potato Early Blight
- Corn Common Rust

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests.

