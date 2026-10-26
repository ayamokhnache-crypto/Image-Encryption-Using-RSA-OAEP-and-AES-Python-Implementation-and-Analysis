# Image-Encryption-Using-RSA-OAEP-and-AES-Python-Implementation-and-Analysis
 This project explores image encryption and decryption using RSA and hybrid public-key encryption techniques. Implemented in Python using a Jupyter Notebook, it focuses on cryptographic algorithms, image processing, and the analysis of encrypted images.The main objective is to analyze their security strength and computational efficiency when applied to images. The methods are evaluated using histogram analysis, correlation coefficients,entropy, and execution time measurements.

## Objectives

- Implement RSA key generation, encryption, and decryption.
- Explore hybrid encryption combining public-key and symmetric-key techniques.
- Implement mathematical operations used in RSA, including modular exponentiation, the greatest common divisor (GCD), and primality testing.
- Apply encryption and decryption to image data.
- Visualize and examine encrypted images.

## Technologies and Libraries

- **Python** — Main programming language.
- **Jupyter Notebook** — Interactive development and experimentation.
- **NumPy** — Numerical and array operations.
- **Pillow** — Image loading and processing.
- **PyCryptodome** — Cryptographic operations, including AES.
- **Matplotlib** — Data visualization and plotting.
- **IPython** — Notebook display functionality.

## Project Structure

```text
.
├── Practical work.ipynb
├── Images
├── Report
└── README.md
```

## How to Run

1. Download or clone this repository.
2. Install the required Python packages listed in `requirements.txt`.
3. Open `Practical work.ipynb` in Jupyter Notebook.
4. Place the input images in the same working directory as the notebook:
   - `Black_and_white_butterfly.png` for the first set of experiments.
   - `Colored_butterfly.png` for the colored-image experiments.
5. Execute the notebook cells in order.
6. When prompted, choose the image mode:
   - `0` — Convert the image to grayscale.
   - `1` — Keep the image in its existing mode.

**Image requirements:** Use PNG images with the exact filenames specified above. For colored-image experiments, use an RGB or RGBA image. For grayscale experiments, the program converts the image to grayscale when option `0` is selected.

The notebook displays the original image, the encrypted image representation, the decrypted image, and the execution time for the relevant experiments.

## Security Note

This project is intended for educational purposes and cryptographic experimentation. A custom implementation of RSA or an encryption scheme should not be considered production-ready without thorough security analysis. In particular, textbook RSA does not provide secure encryption padding, and hybrid encryption requires a secure key-management design.

## Author

Developed as part of an academic practical work on cryptography and image encryption.
