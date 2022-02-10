# Microscopic-Image-analysis

# Tasks:
### 1) Use python to programmatically download/read a 16-bit TIF micrograph with fluorescently labelled cell nuclei from the following location:
https://github.com/Shutterbug2109/Microscopic-Image-analysis/raw/main/Sample.tif
### Once loaded display the images, scale them appropriately to ensure the cell nuclei are visible.
NB: Make sure to import all the necessary libraries allowing you to load raw TIFs.

### 2) Use an arbitrary threshold value (defined manually) to convert nuclei from the grayscale image to a binary mask. Once done - display the mask and the raw image side-by-side.
Optional: find optimal threshold value automatically.

### 3) Measure and display the pixel area of each nucleus. Avoid thresholding artifacts, which differ significantly from the nuclei in certain aspects.

### 4) Using Numpy, create a Python generator producing a 96 by 96 pixel-sized random crop from the original grayscale image.
Optional: Create a generator compatible with the built-in Keras, Tensorflow or PyTorch classes.


# Learnings: 

#### Concepts of Computer Vision and Image analysis
#### Use of Sci-kit Image and OpenCv
#### Python Generator to make a random crop from an image and which is compatible with Keras Tensorflow
