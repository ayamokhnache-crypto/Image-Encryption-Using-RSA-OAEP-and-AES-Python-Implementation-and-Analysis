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
## Security Note

This project is intended for educational purposes and cryptographic experimentation. A custom implementation of RSA or an encryption scheme should not be considered production-ready without thorough security analysis. In particular, textbook RSA does not provide secure encryption padding, and hybrid encryption requires a secure key-management design.

## Author

Developed as part of an academic practical work on cryptography and image encryption.
