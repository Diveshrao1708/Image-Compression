# Image-Compression

This repository contains implementations of two different image compression algorithms: JPEG and LZW. The project demonstrates how images can be compressed and decompressed using these methods, each with its own advantages and use cases.

## Project Structure

- `A4_JPEG.ipynb`: Jupyter notebook containing the implementation of JPEG compression.
- `A4_LZW.ipynb`: Jupyter notebook containing the implementation of LZW compression.
- `images/`: Directory containing sample images used for testing the compression algorithms.

## Features

### JPEG Compression
- **JPEG Compression Algorithm**: Implementation of the Discrete Cosine Transform (DCT), quantization, and entropy encoding.
- **Decompression**: Reconstruction of images from the compressed format, including inverse DCT and dequantization.
- **Visualization**: Comparison of original and compressed images to illustrate the effectiveness of the compression algorithm.

### LZW Compression
- **LZW Compression Algorithm**: Implementation of the LZW compression technique, which encodes data using a dictionary-based approach.
- **Decompression**: Reconstruction of images from the compressed format.
- **Visualization**: Comparison of original and compressed images to illustrate the effectiveness of the compression algorithm.

## Installation

To run the notebooks, you need to have Python and Jupyter Notebook installed. You can install the required libraries using the following command:

```bash
pip install numpy matplotlib opencv-python
