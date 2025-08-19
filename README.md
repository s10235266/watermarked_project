# Image Processing Watermark Project

This project implements image processing techniques for adding and extracting watermarks from images. It utilizes Discrete Cosine Transform (DCT) to embed watermarks in the frequency domain of images, allowing for robust watermarking against various attacks.

## Files in the Project

- **HW4.ipynb**: This Jupyter Notebook contains the main code for image processing and watermarking. It includes functions for adding and extracting watermarks, calculating Peak Signal-to-Noise Ratio (PSNR), and applying various image processing techniques such as Gaussian noise, binary opening, and closing.

- **requirements.txt**: This file lists the necessary Python packages required to run the code in `HW4.ipynb`.

- **README.md**: This documentation file provides an overview of the project, setup instructions, and usage guidelines.

## Setup Instructions

To set up the project, follow these steps:

1. Clone the repository or download the project files to your local machine.

2. Navigate to the project directory.

3. It is recommended to create a virtual environment. You can do this using the following command:
   ```
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

5. Install the required packages using pip:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Open the `HW4.ipynb` file in Jupyter Notebook or any compatible environment.

2. Modify the `input_img_name` and `input_watermark_name` variables to specify the image and watermark files you want to use.

3. Run the cells in the notebook to add a watermark to the image and extract it later.

4. The PSNR value will be calculated to evaluate the quality of the watermarked image.

5. Various image processing techniques can be applied to test the robustness of the watermark against attacks.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.