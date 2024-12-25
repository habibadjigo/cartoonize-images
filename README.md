# cartoonize-images
Image Cartoonization using Pix2Pix GAN. This project transforms real images into cartoon-style using deep learning and OpenCV. Includes code, dataset, and demo.

# Cartoonize Images using Pix2Pix GAN  

This project transforms real-world images into cartoon-style images using a Pix2Pix GAN. The dataset was created using OpenCV for image stylization, and the GAN was trained for image-to-image translation.

## Project Overview  

1. **Objective**:  
   - Convert real images into cartoon-style images using a GAN-based approach.
2. **Steps**:  
   - Dataset preparation (real and cartoonized images).  
   - Model training using the Pix2Pix GAN.  
   - Validation and demo on new images and videos.

## Setup Instructions  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/cartoonize-images.git
   cd cartoonize-images


   Install dependencies:
pip install -r requirements.txt


Prepare the dataset:

Use OpenCV scripts to create cartoonized versions of real images.
Place paired images in the data/ folder


Train the model:
python train_pix2pix.py --dataset_path data/


Test the model on new images:
python test_pix2pix.py --input_path input_images/ --output_path output_images/

File Structure
cartoonize-images/
├── data/                # Dataset (real and cartoonized images)
├── train_pix2pix.py     # Training script
├── test_pix2pix.py      # Testing script
├── README.md            # Project documentation


