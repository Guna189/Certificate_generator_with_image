The Certificate Generator is a Python script that automates the process of generating personalized certificates for various events, courses, workshops, or achievements. It reads participant names and image paths from an Excel file, overlays them on a pre-defined template, and generates both image and PDF versions of the certificates. This documentation provides step-by-step instructions for using the Certificate Generator and outlines the input requirements and usage guidelines.
Steps to Use the Certificate Generator
1.Prerequisites
Install Python: Ensure you have Python installed on your computer.
Install Libraries: Install the required libraries using the following command: pip install openpyxl opencv-python Pillow 
2.Input Data
Certificate Template: Prepare a certificate template in PNG format(preferred). Replace TEMPLATE.png with the path to your template in the script.
Certified Names: Create an Excel file (EXCELSHHET.xlsx) containing participant names in the first column and corresponding image paths in the second column. The data should start from the third row, with headers in the first and second rows.
3.Configuration
Adjust Font Size and Color: Modify font_size and font_color variables to customize the appearance of participant names on the certificates.
Set Number of Certificates:Change the value of n to specify the number of certificates to be generated (starting from the third row in the Excel file).
4.Certificate Name Co-ordinates
•	To adjust the position of the participant's name on the certificate template, modify x_corr and y_corr. These values control the horizontal and vertical positions, respectively.
5.Participant Image
Replace "/PATH.PNG" with the actual path to the participant's image. Ensure that the image is of suitable dimensions (330x440 pixels) for optimal display on the certificate.
6.Certificate Generation
Run the script.
