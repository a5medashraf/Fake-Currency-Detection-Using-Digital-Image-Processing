# Fake-Currency-Detection-Using-Digital-Image-Processing

## Introduction
Fake currency is a significant issue faced by financial institutions and individuals worldwide. Counterfeit money can have severe economic consequences, leading to financial losses and undermining the trust in the monetary system. To combat this problem, digital image processing techniques can be employed to detect fake currency notes.

This project aims to develop a system that leverages digital image processing algorithms to detect counterfeit currency. By analyzing various features and patterns on currency notes, the system can identify potential discrepancies that indicate the presence of fake currency.

## Methodology
### Method 1: UltraViolet effect
The first method in the fake currency detection process is simulating the **ultraviolet effect** on the fake image. 
This method is based on this [Paper](https://www.researchgate.net/publication/365977982_COUNTERFEIT_CURRENCY_DETECTION_USING_IMAGE_PROCESSING).
The following steps are followed in this method:

1. Convert the Image to HSV Color Space
2. Apply Histogram Equalization on The Image
3. Compare the mean saturation of the current Image with the reference image


### Method 2: Feature Extraction
The first method in the fake currency detection process is **extracting features** from the Current image and comparing them with the extracted features of the reference Image.
The features that we have focused on are **(Blendlines, Serial number & Font size).**
The following steps are followed in this method:

1. Convert the Image to gray Color Space
2. use the canny detector to detect edges
3. Apply Closing to connect objects to each other
4. Apply Region filling
5. Apply Edge-based segmentation

### Results

<img
  src="xyyz.JPG"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

### References
- https://www.researchgate.net/publication/365977982_COUNTERFEIT_CURRENCY_DETECTION_USING_IMAGE_PROCESSING
- https://iopscience.iop.org/article/10.1088/1757-899X/263/5/052047
- https://ijcsmc.com/docs/papers/April2019/V8I4201914.pdf
- https://www.mintageworld.com/knowledge-base/security-features-on-current-banknotes/







This method is based on this [Paper](https://www.researchgate.net/publication/365977982_COUNTERFEIT_CURRENCY_DETECTION_USING_IMAGE_PROCESSING).

https://iopscience.iop.org/article/10.1088/1757-899X/263/5/052047
