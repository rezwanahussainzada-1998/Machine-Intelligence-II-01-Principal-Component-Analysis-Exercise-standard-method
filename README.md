**Principal Component Analysis (PCA) & Image Reconstruction**

This repository focuses on the foundational concepts and practical applications of Principal Component Analysis (PCA). It demonstrates how PCA can be used for both low-dimensional dataset analysis and high-dimensional data compression, specifically focusing on structural features in image processing.

**Key Features & Explorations**

2-Dimensional Toy Data Analysis: Implemented data centering, covariance matrix estimation, and eigenvalue decomposition from scratch. Visualized the principal components as orthogonal axes to identify the direction of maximum variance.

Image Patch Extraction & Preprocessing: Processed natural and text images by breaking them down into small patches (12x12 pixels), flattening them into high-dimensional vectors, and centering the patch distributions.

Eigenimages & Basis Functions: Computed the principal components (eigenvalues and eigenvectors) of the image patches to extract the dominant visual features, forming a set of optimal basis functions known as eigenimages.

Image Compression & Reconstruction: Reconstructed the original images using a subset of the top M principal components (varying M from 1 to 100). Analyzed the trade-off between compression rate and visual quality, comparing how the model retains structural vs. textual information.

**Repository Structure**

sheet01_MI2.pdf: The detailed academic report including theoretical explanations, mathematical formulas, and comprehensive visual results of the reconstructed images.

Jupyter Notebook: The complete Python implementation utilizing NumPy, Matplotlib, and Pillow (PIL) for data handling, PCA calculations, and image patch processing.

Note: For the full analysis, comparative plots, and mathematical details regarding the reconstruction error, please refer to the attached PDF report.
