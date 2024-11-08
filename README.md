### Project Overview ###

**This project, developed using UiPath Studio by Mr.Smile, automates the extraction of data from multiple PDF files located in a folder named (Receipts).The PDFs are in image format, requiring Optical Character Recognition (OCR) to convert images into text. The robot processes this text to extract specific values and saves them in an Excel spreadsheet.**

1.**Table of Contents**
* Prerequisites*
* How It Works*
* Installation*
* Usage*
* Post-Conditions*
* Contact Information*

// Prerequisites
- UiPath Studio installed on your machine.
- Access to the folder containing PDF files named "Receipts."
- Excel installed or access to a compatible spreadsheet application.
- Required UiPath packages for OCR and Excel activities.

// How It Works
- Precondition Check: The robot checks if the "Receipts" folder contains any PDF files.
- Data Extraction: If PDF files are found, the robot uses OCR to extract text from each file.
- Data Processing: The robot processes the extracted text to identify and retrieve specific values.
- Excel Integration: The extracted values are added to an existing Excel spreadsheet.

// Installation
- Clone or download this repository to your local machine.
- Open UiPath Studio and create a new project.
- Import the workflow files from this repository.
- Ensure all necessary dependencies are installed via the "Manage Packages" option in UiPath Studio.

// Usage
- Place your PDF files in the "Receipts" folder.
- Open the main workflow in UiPath Studio.
- Run the robot to start the data extraction and processing.
- Check the designated Excel file for the extracted data.

//Post-Conditions
- The robot confirms that the Excel file already exists before adding the extracted data.
- Upon successful execution, the robot logs the results of the data extraction process.

//Contact Information
For any questions or issues, please contact:

- Mr. Smile
- https://www.linkedin.com/in/nabilwilliam/
