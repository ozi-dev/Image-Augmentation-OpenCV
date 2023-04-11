
# Image Data Augmentation using OpenCV

This code is designed to perform image data augmentation on a folder of images using OpenCV library at **Google Colab**. This technique is used to increase the size of the available dataset by creating multiple new and distinct images from the existing ones. The code can be used for any image dataset, just make sure to specify the correct path to the input folder and output folder. For scraping images visit repo that written by me: <a href="https://github.com/ozi-dev/img-scrapper">img-scraper</a> 

## Prerequisites

- Google Colab account
- Python 3.x
- OpenCV 
- Numpy 

### Installation

1. Clone this repository by running the following command in your terminal:

```
git clone https://github.com/your_username/art-augmentation.git
```

2. Install required packages using pip:

```
pip install opencv-python google-colab numpy
```

3. Add the images you want to augment to a new folder in your Google Drive account.

## Usage

1. Open `art_augmentation.ipynb` file in Google Colab.
2. Replace "your_folder_name" and "your_output_folder_name" with the names of your input and output folders respectively.
3. Run each cell of the notebook step-by-step.

After running the script, new images will be generated and saved to the output folder in your Google Drive account.
##  Augmentation Techniques Used
The following augmentation techniques are applied to each image:
- Flipping the image horizontally
- Rotating the image by 90 degrees clockwise
- Applying Gaussian blur to the image
- Converting the image to grayscale
- Converting the image to HSV color space 
## Contact
Author: Oğuzhan Öztürk

Email: oguzhanozturk0@outlook.com
