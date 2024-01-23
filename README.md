# Assignment Solution README

## Overview

This repository contains the solution for the assignment. The main solution file is `upscale_final.ipynb`, which is a Jupyter Notebook.

## Usage

To use the solution, follow the steps below:

1. Open `upscale_final.ipynb` in Jupyter Notebook.
2. Navigate to the main cell that contains input parameters.
3. Modify the following input parameters based on your requirements:

    - `input_video_path`: Provide the path to the input video file.
    - `final_output_path`: Set the desired path for the final upscaled output.
    - `new_resolution`: Specify the desired dimensions for the new resolution.

4. Run the notebook cell by cell, making sure all dependencies are installed.

## Input Parameters

The main cell in the notebook contains the following input parameters:

```python
# Input Parameters
input_video_path = "path/to/your/input/video.mp4"
final_output_path = "path/to/your/output/output_final.mp4"
new_resolution = (1280, 720)  # Set your desired resolution