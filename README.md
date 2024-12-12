# IoU and Dice Coefficient Calculation Script

This repository provides a Python script for calculating Intersection over Union (IoU) and Dice Coefficient between two images using Google Colab.

## Objective
We run the code to animate children's drawings (https://github.com/facebookresearch/AnimatedDrawings/blob/main/README.md). After running the code, the segmentation mask will be generated for each uploaded picture. The code here is designed to test how well the model handles the generated segmentation masks.

## Features
- Upload and process two images: a mask (ground truth) and a texture (predicted).
- Automatically resizes and binarizes the images for accurate comparison.
- Computes IoU and Dice Coefficient metrics.
- Displays the binary versions of the input images for visual verification.

## Usage

### Clone the repository:
```bash
git clone [https://github.com/your-username/repository-name.git](https://github.com/anhthach375/AnimatedDrawings_341CV.git)
cd AnimatedDrawings_341CV
```

### Open the script:
Open the `iou_dice_calculation.ipynb` file in Google Colab or Jupyter Notebook.
[Link to Colab](https://colab.research.google.com/drive/1ayTfQarv4x5oqpBRtx21rQafBU03g5rG?authuser=2)


### Upload your files when prompted:
- The first uploaded image will be treated as the mask (ground truth).
- The second uploaded image will be treated as the texture (predicted).

### Run the script to:
- Compute IoU and Dice Coefficient.
- Display binary versions of the images for verification.

## Output Example

Console Output:
```
IoU: 0.3577
Dice Coefficient: 0.5689
```

Displayed Images:
- **Left:** Binary version of the original texture image.
- **Right:** Binary version of the mask image.

Example of expected output:
<img width="686" alt="Screenshot 2024-12-11 at 7 25 42 AM" src="https://github.com/user-attachments/assets/5ed102e1-e415-47e9-b12c-454ffb454111">


## Troubleshooting
- **Image Load Error:** Ensure the uploaded files are valid image formats (e.g., PNG, JPG).
- **Unexpected Results:** Verify the image content and adjust the thresholding parameters if necessary.

## Contributions
Feel free to fork this repository and submit a pull request for improvements or bug fixes.

