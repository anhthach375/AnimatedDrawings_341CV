# IoU and Dice Coefficient Calculation Script

This repository provides a Python script for calculating Intersection over Union (IoU) and Dice Coefficient between two images using Google Colab.

## Features
- Upload and process two images: a mask (ground truth) and a texture (predicted).
- Automatically resizes and binarizes the images for accurate comparison.
- Computes IoU and Dice Coefficient metrics.
- Displays the binary versions of the input images for visual verification.

## Usage

### Clone the repository:
```bash
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

### Open the script:
Open the `iou_dice_calculation.ipynb` file in Google Colab or Jupyter Notebook.

### Upload your files when prompted:
- The first uploaded image will be treated as the mask (ground truth).
- The second uploaded image will be treated as the texture (predicted).

### Run the script to:
- Compute IoU and Dice Coefficient.
- Display binary versions of the images for verification.

## Output Example

Console Output:
```
IoU: 0.7854
Dice Coefficient: 0.8793
```

Displayed Images:
- **Left:** Binary version of the original texture image.
- **Right:** Binary version of the mask image.

## Troubleshooting
- **Image Load Error:** Ensure the uploaded files are valid image formats (e.g., PNG, JPG).
- **Unexpected Results:** Verify the image content and adjust the thresholding parameters if necessary.

## Contributions
Feel free to fork this repository and submit a pull request for improvements or bug fixes.
