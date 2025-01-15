# Image to Speech Conversion

This project demonstrates a method to process images and convert their contents into speech using Python. The Jupyter Notebook provided (`img_to_speach.ipynb`) contains all the steps and code necessary to perform this task.

## Features
- **Image Preprocessing**: Load and preprocess images for text extraction.
- **Text Extraction**: Use Optical Character Recognition (OCR) to extract text from images.
- **Text-to-Speech Conversion**: Convert extracted text into speech audio files.

## Prerequisites
To run the notebook, you will need:
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Required Libraries
The following Python libraries are used in this project:
- `pytesseract`: For Optical Character Recognition (OCR).
- `Pillow`: For image processing.
- `gTTS`: For text-to-speech conversion.
- `IPython.display`: To play audio files directly in the notebook.

You can install these libraries using pip:
```bash
pip install pytesseract pillow gTTS
```

### Additional Requirements
- **Tesseract OCR**: You need to install Tesseract OCR separately. Follow the instructions for your platform:
  - **Windows**: Download the installer from [Tesseract OCR Github](https://github.com/tesseract-ocr/tesseract).
  - **macOS**: Install via Homebrew:
    ```bash
    brew install tesseract
    ```
  - **Linux**: Install using the package manager:
    ```bash
    sudo apt-get install tesseract-ocr
    ```

## Usage
1. Clone the repository or download the `img_to_speach.ipynb` file.
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook img_to_speach.ipynb
   ```
3. Follow the instructions in the notebook to:
   - Load your image files.
   - Extract text from images.
   - Convert the extracted text into speech.

## Example
1. **Input**: An image containing text (e.g., a scanned document or a signboard).
2. **Output**: A speech file (e.g., `output.mp3`) that vocalizes the text from the image.

## Notes
- Ensure that the images have clear and legible text for optimal OCR performance.
- You can customize the voice, language, and speed of the speech output by modifying the parameters in the `gTTS` function.

## Contributing
Feel free to fork the repository and submit pull requests. Suggestions and feedback are welcome!

