# flask-cifar10-classifier
# Image Classification with CNN and Flask

This project demonstrates how to create an image classification application using a Convolutional Neural Network (CNN) model trained on the CIFAR-10 dataset. The web interface is built using Flask.

## Project Structure

- `train_model.py`: This script trains a CNN model on the CIFAR-10 dataset and saves the trained model.
- `image_classifier.py`: This is the Flask web application that allows users to upload images and get predictions from the trained model.
- `templates/index.html`: HTML template for the Flask web application.

## Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.9
- Conda (for creating and managing virtual environments)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name

2.Create and activate a virtual environment:

  conda create -n flask_env python=3.9
  conda activate flask_env

3.	Install the required packages:

pip install tensorflow keras numpy matplotlib flask flask-bootstrap pillow


Training the Model

	1.	Run the train_model.py script to train the CNN model on the CIFAR-10 dataset:

 python train_model.py

 This script will train the model and save it as cifar10_model.h5.

Running the Flask App

	1.	Start the Flask application:

 python image_classifier.py

 2.	Open your web browser and go to:

http://localhost:5000

3.	Upload an image and see the prediction.

Contributing

	1.	Fork the repository.
	2.	Create a new branch (git checkout -b feature-branch).
	3.	Commit your changes (git commit -m 'Add new feature').
	4.	Push to the branch (git push origin feature-branch).
	5.	Create a new Pull Request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

	•	The CIFAR-10 dataset: CIFAR-10
	•	Flask documentation: Flask

Suheyl Ozdemir
Data Scientist & AI Volunteer

    
