# Fake-Currency-Detection-Using-Digital-Image-Processing

## Introduction
Fake currency is a significant issue faced by financial institutions and individuals worldwide. Counterfeit money can have severe economic consequences, leading to financial losses and undermining the trust in the monetary system. To combat this problem, digital image processing techniques can be employed to detect fake currency notes.

This project aims to develop a system that leverages digital image processing algorithms to detect counterfeit currency. By analyzing various features and patterns on currency notes, the system can identify potential discrepancies that indicate the presence of fake currency.

## Methodology
### Method 1: Feature Extraction
The first step in the fake currency detection process is feature extraction. This involves extracting key features and characteristics from the currency note images. The following steps are followed in this method:

1. Watermarks: Extract and analyze watermarks embedded in the currency note design.
2. Microprint: Detect and examine microprinted text or patterns that are often present on genuine currency notes.
3. Serial numbers: Extract and compare the serial numbers on the notes to identify any inconsistencies.
4. Security threads: Analyze the presence and characteristics of security threads embedded in the notes.
5. These features are extracted using digital image processing techniques such as edge detection, thresholding, and template matching.

### Method 2: Pattern Recognition
The second method employed in fake currency detection is pattern recognition. In this step, the extracted features are compared against a reference database of genuine currency features. The system uses pattern matching algorithms to determine the similarity between the features extracted from the input currency note and the reference features.

Pattern recognition techniques, such as correlation-based matching or machine learning algorithms, can be used to identify potential matches and calculate a similarity score. If the similarity score falls below a predefined threshold, the note is flagged as potentially counterfeit.
