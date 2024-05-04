# Image Captioning with multilingual text to speech

## Description

This project involves development of Image captioning system that provides descriptive interpretations of images in multiple languages of choice with text to speech. 

## Installation

### Prerequisites
- Python (version 3.11.4)

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/kirankumarkanaje/image_captioning_nlp.git
    ```

2. Navigate to the project directory:
    ```bash
    cd image_captioning_nlp
    ```

3. Install the required Python packages using pip:
    ```bash
    pip install -r requirements.txt
    ```

   This will install all the necessary dependencies listed in `requirements.txt`.

4. Download the two zip files('Dataset.zip' & 'working.zip') from the below link and then extract them. Then, replace the existing folders ('Dataset' & 'working') in the project directory with the current extracted folders.
   
   Link: https://drive.google.com/drive/folders/1kGu9LTNfk6tFSfRuab9jpFLiaaT16ZUf?usp=sharing

## Usage

### Running Inference

To perform inference using the provided model, follow these steps:

1. Navigate to the project directory:
    ```bash
    cd image_captioning_nlp
    ```

2. Open the inference notebook:
    ```bash
    jupyter notebook inference.ipynb
    ```
3. In the `inference.ipynb` notebook, execute the cells sequentially to perform the inference process. This involves loading the trained model, processing test images(stored in TestImages folder), generating captions, translating captions, and producing audio for the captions.
   
    **Note:** Ensure you have all the necessary dependencies installed for the notebook to run smoothly. Also, make sure to select the correct kernel (Python environment) before executing the cells.
