# PCD_Assignment01

## Down Sampling and Up Sampling

This assignment explores the effects of different downsampling and upsampling methods on digital images.

### Methods

**Downsampling**
- Max
- Average
- Median

**Upsampling**
- Nearest Neighbor (NN)
- Bilinear
- Bicubic

### Input Images

Four images with different characteristics are used for the experiment:

- `cat.jpg` — grayscale image with detailed fur and clear edges.
- `owl.jpg` — color image with detailed feathers and background.
- `gelex.jpg` — colorful image with high contrast and bright regions.
- `photostrip.jpg` — image containing photographs, text, and fine details.

### Experiment

The images are first downsampled by a factor of 2 using Max, Average, and Median methods.

The original images are also upsampled by a factor of 2 using Nearest Neighbor, Bilinear, and Bicubic interpolation.

An additional experiment performs Average downsampling followed by upsampling using the three interpolation methods to observe the effects of information loss and image reconstruction.

### Files

- `PCD_Assignment01.ipynb` — Google Colab notebook containing the source code and experiment results.
- `Report_Analysis.pdf` — report containing the analysis and conclusion.
- `cat.jpg` — input image.
- `owl.jpg` — input image.
- `gelex.jpg` — input image.
- `photostrip.jpg` — input image.

### Results

The experiment demonstrates that different sampling methods produce different visual results. Downsampling reduces spatial information, while upsampling uses interpolation to estimate new pixel values. Nearest Neighbor produces a more pixelated result, while Bilinear and Bicubic produce smoother results.

### Author

**Mazaya Nurina**  
**NIM:** 25/554758/PA/23236
