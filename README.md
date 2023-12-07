# Image Classifier Web Application

This is a web application built with Flask for image classification using a pre-trained neural network model. It allows users to upload images or provide image URLs to classify objects into predefined categories.
![HomePage](https://github.com/abhayrajnavodayan/Multi_Image_Classifier/blob/main/ScreenShots/HomePage.png)
![ResultPage](https://github.com/abhayrajnavodayan/Multi_Image_Classifier/blob/main/ScreenShots/ResultPage.png)


## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Features

- Upload and classify local images (JPG, JPEG, PNG).
- Classify images by providing URLs.
- Display the top 3 predicted classes and their probabilities.
- Built with Flask, TensorFlow/Keras, and PIL.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your local machine.
- Required Python packages listed in `requirements.txt`.
- A pre-trained neural network model saved as `model.hdf5`.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/abhayrajnavodayan/Multi_Image_Classifier.git
   cd image-classifier-app
   ```
   
2. Navigate to the project folder and make a virtual environment
   ```bash
   python -m veny myenv
   ```
3. Activate the environment
   ```bash
   myenv\Scripts\activate
   ```
   
4. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
5. Start the Flask application:
   ```bash
   python app.py
   ```
   Open a web browser and go to http://localhost:5000 to access the application.<br>
   Use the web interface to either upload an image or provide an image URL for classification.<br>
   ##### Note that you need to paste secure image adress link, for example that starts with https:// <br>
   The application will display the top 3 predicted classes and their probabilities.


## Troubleshooting
   If you encounter issues while running the application, consider the following troubleshooting steps: <br>
   * Check file paths and permissions for image files and the model.
* Ensure the required Python packages are installed.
* Review error messages in the terminal for more information.
* Clear your browser cache if the webpage is not rendering as expected.

## Contributing
  Contributions are welcome! If you find a bug or have suggestions for improvements, please open an issue or create a pull request.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

# <sup>[Back to Top](#table-of-contents)</sup>




   
