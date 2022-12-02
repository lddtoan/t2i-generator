# Text to Image Generator

Text to Image generator based on DALL-E.

Reference [DALLE-Pytorch](https://github.com/lucidrains/DALLE-pytorch)

## Prerequisites

> Python 3.10.8

> Microsoft Visual C++ 14.0

> CUDA Toolkit 11.7

## Setup

Run `setup.bat` file.

## Usage

Training model

`python train.py --image_text_folder ./dataset --taming --truncate_captions`

Generate image

`python generate.py --dalle_path ./dalle.pt --text "blue jacket"`
