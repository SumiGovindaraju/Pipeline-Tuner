# Pipeline-Tuner
This repository is for a GUI that allows you to tune the HSV thresholding values for use in a vision pipeline. The minimum and maximum HSV values are saved in a JSON file called `config.json`.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development, testing, and use.

### Dependencies
- [OpenCV](https://www.opencv.org/)
- [NumPy](http://www.numpy.org/)
- [Python Imaging Library](http://www.pythonware.com/products/pil/)

### Installing
- Clone this repository (`git clone https://github.com/SumiGovindaraju/Pipeline-Tuner.git`)
- Download and Install [Python 2.7](https://www.python.org/download/releases/2.7/)
- Install [PIP](https://pip.pypa.io/en/stable/installing/)
- Install OpenCV and NumPy (`pip install opencv-python`)
- Install PIL (`pip install Pillow`)
- Run the tuner (`python tuner.py`)