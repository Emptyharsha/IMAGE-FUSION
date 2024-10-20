# IMAGE-FUSION
Based on the files extracted from the provided ZIP and the information in the existing project, here’s a revised version of the README file for your image fusion project:

---

# Image Fusion Desktop App

This project is an open-source desktop application that allows users to fuse multiple images using **Discrete Wavelet Transformation (DWT)**. The fusion process helps create more detailed images by combining the strengths of each input image.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Future Improvements](#future-improvements)
- [License](#license)

## Introduction

**Image Fusion** is the process of combining relevant information from two or more images into a single image that is more informative and suitable for human perception or further processing tasks. A common example includes the fusion of MRI and CT scans in the medical field, where both scans provide complementary information about the brain's structure and tissues.

This desktop application focuses on image fusion using **Discrete Wavelet Transformation (DWT)**, an efficient and commonly used method in image processing.

### What is Discrete Wavelet Transformation (DWT)?

DWT decomposes images into various components, which allows for detailed analysis and fusion at multiple resolution levels. This technique ensures that important features from each input image are preserved in the final fused image.

## Features

- **Multiple Image Fusion**: Fuse two or more images to create a single, more detailed output.
- **DWT-Based Fusion**: Efficient fusion using wavelet transformation.
- **Support for Various Use Cases**: Useful for medical imaging, surveillance, and other fields where combining visual information is beneficial.
- **Image Restoration and Mixing**: Capabilities for image restoration and mixing of faulty images.

## Technologies Used

- **Python**: Core programming language used for developing the application.
- **PyQt**: For building the desktop application interface.
- **OpenCV**: For image processing operations.
- **Numpy**: For handling matrix and array operations.
- **Matplotlib**: For displaying images and outputs.
  
## Installation

To set up the project locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/image-fusion.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-fusion
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the main Python script to launch the desktop app:
   ```bash
   python fusion_main.py
   ```
2. Use the interface to load the images you want to fuse.
3. Select the image fusion method and click "Fuse" to generate the output.
4. Save the resulting fused image.

## Screenshots

Below are a few examples of the application and its image fusion capabilities:

### Medical Image Fusion
| CT Scan | MRI Scan | Fused Image |
| --- | --- | --- |
| ![CT Scan](screenshots/medical1.png) | ![MRI Scan](screenshots/medical2.png) | ![Fused Image](screenshots/out1956.jpg) |

### Image Mixing
| Image 1 | Image 2 | Fused Image |
| --- | --- | --- |
| ![Image 1](screenshots/person1.png) | ![Image 2](screenshots/person2.png) | ![Fused Image](screenshots/Screenshot_from_2020-12-21_02-15-37.png) |

## Future Improvements

- **Additional Algorithms**: Support for other image fusion techniques such as **Discrete Cosine Transform (DCT)** and **Principal Component Analysis (PCA)**.
- **User Controls**: More options for users to customize the fusion process, including changing operation modes.
- **Improved Interface**: A more intuitive user interface for a better user experience.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

This README gives an overview of the project, its functionality, and its future improvements, while incorporating details found in the extracted files. Let me know if you'd like to make further adjustments!
