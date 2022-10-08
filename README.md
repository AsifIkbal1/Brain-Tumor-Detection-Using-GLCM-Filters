# Brain-Tumor-Detection-Using-GLCM-Filters
Brain Tumor Detection Using GLCM &amp; Filters
# GLCM
A statistical method of examining texture that considers the spatial relationship of pixels is the gray-level co-occurrence matrix (GLCM), also known as the gray-level spatial dependence matrix. The GLCM functions characterize the texture of an image by calculating how often pairs of pixel with specific values and in a specified spatial relationship occur in an image, creating a GLCM, and then extracting statistical measures from this matrix. (The texture filter functions, described in Calculate Statistical Measures of Texture cannot provide information about shape, that is, the spatial relationships of pixels in an image.)

After you create the GLCMs using graycomatrix, you can derive several statistics from them using graycoprops. These statistics provide information about the texture of an image.

* **greycomatrix** - calculate the grey-level co-occurrence matrix
* **greycoprops** - calculate texture properties of a GLCM

Texture properties can be 
1. **Contrast** - Measures the local variations in the gray-level co-occurrence matrix.

2. **Correlation** - Measures the joint probability occurrence of the specified pixel pairs.

3. **Energy** - Provides the sum of squared elements in the GLCM. Also known as uniformity or the angular second moment.

4. **Homogeneity** - Measures the closeness of the distribution of elements in the GLCM to the GLCM diagonal.
