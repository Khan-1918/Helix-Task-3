# Helix-Task-3
Image Analysis and Attribute Extraction Documentation

Objective:
To analyze images, validate their format and dimensions, and extract specific attributes (e.g., Serial Number, Model Number, Manufacturer Name) using PaddleOCR.

Workflow Summary
Mount Google Drive:

Ensure access to the directory containing the images.
Step 1: Analyze Image Formats and Dimensions:

Count the number of .jpg, .jpeg, and .png files.
Validate the readability of each image and log their dimensions.
Identify and flag unreadable files.

Step 2: Extract Attributes Using PaddleOCR:

Apply OCR to extract text from images.
Parse extracted text for attributes such as:
Serial Number
Model Number
Manufacturer Name
Log images with successfully extracted attributes and flag failed extractions.

Step 3: Save Results:

Store the extracted attributes in a CSV file for further analysis.

Outputs
Image Format Counts:


Count of readable and unreadable images.
Extracted Attributes:

Key attributes (Serial Number, Model Number, Manufacturer Name) saved in a CSV file.

Processing Summary:

Total number of images processed.
Number of successful and failed extractions.
Location of the results file.

Deliverables
CSV File:

Contains extracted attributes for each processed image.
Stored at: /content/drive/MyDrive/paddle1.csv

Logs:

Details of processed images, including dimensions and attribute extraction status.

Insights:

Distribution of file formats.
Success rate of OCR-based attribute extraction.

Conclusion
This workflow ensures accurate image validation and extraction of key attributes, resulting in a structured dataset for analysis. The use of PaddleOCR enhances the efficiency and accuracy of text extraction.

