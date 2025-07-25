# Image Registration

This repository contains a simple Python-based image registration code.

## Features

- Aligns images using feature-based or intensity-based methods
- Supports common image formats (JPEG, PNG, TIFF)
- Easy-to-use command-line interface

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

## Installation

```bash
pip install opencv-python numpy
```

## Usage

```bash
python register.py --ref reference.jpg --mov moving.jpg --out output.jpg
```

## Example

```bash
python register.py --ref img1.jpg --mov img2.jpg --out aligned.jpg
```

## License

MIT License
