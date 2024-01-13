# Edge_Detection_techniques


## Project Overview

This project delves into advanced image processing techniques, focusing on edge detection methods. It covers the implementation of convolution operations, Canny edge detection, and Laplacian edge detection, each of which plays a crucial role in feature extraction in images.

### Key Features

#### Task 1: Convolution Function

- **Convolve Function**: Implementation of a custom convolution function, essential for applying various filters and operations on images.

#### Task 2: Canny Edge Detection

- **Non-Maximal Suppression**: A technique to thin out the edges detected by the gradient method, ensuring precision in edge representation.
- **Double Thresholding**: Implementation of a method to identify strong, weak, and non-relevant pixels, crucial for accurate edge detection.
- **Hysteresis Mechanism**: A process to convert weak pixels into strong ones based on the connectivity to strong pixels, enhancing the quality of edge detection.

#### Task 3: Laplacian Edge Detection

- **LoG Mask Creation**: Writing the implementation for creating a Laplacian of Gaussian (LoG) mask, which helps in highlighting regions of rapid intensity change.
- **Zero Crossing Mechanism**: Implementing a method to detect edges based on the zero-crossings after applying the LoG mask, which is effective in highlighting finer details in images.

#### Task 4: Comparative Analysis

- **Laplacian vs. Canny**: The notebook includes a detailed comparison, mentioning where it would be preferred to use the Laplacian method over the Canny method and vice versa. This analysis helps in understanding the practical applications and effectiveness of each method in different scenarios.

