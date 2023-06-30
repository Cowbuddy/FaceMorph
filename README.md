# Face Morph

This project aims to demonstrate face morphing using Python and the OpenCV library. The process involves the following steps:

- Selecting Correspondence Points: We will begin by selecting multiple points of correspondence on the input images.
- Performing Delaunay Triangulations: The selected points will be used to perform Delaunay triangulations, dividing the images into triangles.
- Warping Triangles: Affine transformations will be applied to warp the triangles based on the correspondence points.
- Cross-Dissolving Colors: The colors of the triangles will be cross-dissolved using alpha blending, resulting in a morphed image.
- Generating a Morphing Video: Finally, we will create a video to showcase the morphing process.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

1. Clone to your project directory
```bash
git clone https://github.com/Cowbuddy/FaceMorph.git
```
2. Set up a virtual environment and activate it. Python 3.9.13 works best, but you can use another compatible version if you'd like

Linux/MacOS:
```bash
python3 -m venv env
source env/bin/activate
```

Windows:
```bash
python3 -m venv env
env\Scripts\activate
```

3. All required libraries can be found within the `requirements.txt`. Install the required libraries by running the following command from the project's root directory:

```bash
pip install -r requirements.txt
```

4. Make sure that your Jupyter Notebook is using the virtual environment kernel

By following these installation steps, you will have the project set up with the required dependencies and be ready to work with the Jupyter Notebook using the virtual environment kernel.

## Usage

To use this repository, follow the steps below:

1. Open the Jupyter Notebook file (ipynb extension) in your preferred Jupyter Notebook environment.

2. Execute each code block within the notebook in sequential order. You can run a code block by clicking on it and then pressing Shift+Enter or by using the "Run" button in the toolbar. Running the code blocks in order ensures that the necessary functions and variables are defined and used correctly.

3. If you want to change the input images, you can add your own images to the inputs folder. The provided sample images in the folder are there for you to quickly try out the code. (Outputs are also provided!)

4. The output images will be saved in a folder within the outputs directory. This folder will contain the morphed images and also the images with Delaunay triangles graphed on them.

**Note:** This repository is still a work in progress (WIP), so the best results are obtained when using portrait pictures in `.jpg` format that ideally have the same size. Keep in mind that the face morphing may not produce optimal results with images that deviate significantly from these characteristics.

Feel free to explore the code and experiment with different images to observe the morphing results!