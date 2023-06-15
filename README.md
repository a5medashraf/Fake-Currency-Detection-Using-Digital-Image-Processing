![image](https://github.com/a5medashraf/Fake-Currency-Detection-Using-Digital-Image-Processing/assets/72763763/9ef1ea0e-114a-4ed7-93c1-e73d361eda59)# Fake-Currency-Detection-Using-Digital-Image-Processing

## Introduction
Fake currency is a significant issue faced by financial institutions and individuals worldwide. Counterfeit money can have severe economic consequences, leading to financial losses and undermining the trust in the monetary system. To combat this problem, digital image processing techniques can be employed to detect fake currency notes.

This project aims to develop a system that leverages digital image processing algorithms to detect counterfeit currency. By analyzing various features and patterns on currency notes, the system can identify potential discrepancies that indicate the presence of fake currency.

## Methodology
### Method 1: UltraViolet effect
The first method in the fake currency detection process is simulating the **ultraviolet effect** on the fake image. This method is based on this [Paper](https://www.researchgate.net/publication/365977982_COUNTERFEIT_CURRENCY_DETECTION_USING_IMAGE_PROCESSING).
The following steps are followed in this method:

1. Convert the Image to HSV Color Space
2. Apply Histogram Equalization on The Image
3. Compare the mean saturation of the current Image with the reference image.


### Method 2: Pattern Recognition
The second method employed in fake currency detection is pattern recognition. In this step, the extracted features are compared against a reference database of genuine currency features. The system uses pattern matching algorithms to determine the similarity between the features extracted from the input currency note and the reference features.

Pattern recognition techniques, such as correlation-based matching or machine learning algorithms, can be used to identify potential matches and calculate a similarity score. If the similarity score falls below a predefined threshold, the note is flagged as potentially counterfeit.
