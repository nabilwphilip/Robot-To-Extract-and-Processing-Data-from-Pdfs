### Project Overview ###

**This project, developed using UiPath Studio by Mr.Smile, automates the extraction of data from multiple PDF files located in a folder named (Receipts).The PDFs are in image format, requiring Optical Character Recognition (OCR) to convert images into text. The robot processes this text to extract specific values and saves them in an Excel spreadsheet.**

### Table of Contents ###
1. Prerequisites
2. How It Works
3. Installation
4. Usage
5. Post-Conditions
6. Contact Information

1. **Prerequisites**
* UiPath Studio installed on your machine.
* Access to the folder containing PDF files named "Receipts."
* Excel installed or access to a compatible spreadsheet application.
* Required UiPath packages for OCR and Excel activities.

2. **How It Works**
* Precondition Check: The robot checks if the "Receipts" folder contains any PDF files.
* Data Extraction: If PDF files are found, the robot uses OCR to extract text from each file.
* Data Processing: The robot processes the extracted text to identify and retrieve specific values.
* Excel Integration: The extracted values are added to an existing Excel spreadsheet.

3. **Installation**
* Clone or download this repository to your local machine.
* Open UiPath Studio and create a new project.
* Import the workflow files from this repository.
* Ensure all necessary dependencies are installed via the "Manage Packages" option in UiPath Studio.

4. **Usage**
* Place your PDF files in the "Receipts" folder.
* Open the main workflow in UiPath Studio.
* Run the robot to start the data extraction and processing.
* Check the designated Excel file for the extracted data.

5. **Post-Conditions**
* The robot confirms that the Excel file already exists before adding the extracted data.
* Upon successful execution, the robot logs the results of the data extraction process.

6. **Contact Information**
For any questions or issues, please contact:
--------------------------------------------
* Mr. Smile
* https://www.linkedin.com/in/nabilwilliam/
