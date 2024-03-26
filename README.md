# Bizcardx

Bizcardx is a Streamlit web application for extracting business card data using EasyOCR.

## Introduction

Bizcardx allows users to upload images of business cards and extract relevant information such as company name, cardholder name, designation, contact details, etc. The extracted data can then be displayed and stored in a SQLite database.

## Installation

To run Bizcardx locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:  pip install -r requirements.txt
3. Run the Streamlit application: streamlit run app.py

## Usage

1. Select the "Upload & Extract" option from the sidebar.
2. Upload an image of a business card.
3. The application will extract information from the uploaded image and display it.
4. Optionally, you can upload the extracted data to a database using the "Upload to Database" button.

## Features

- Upload and extract data from business card images.
- Display extracted information and preview the uploaded image.
- Store extracted data in a SQLite database.

## Contributing

Contributions to Bizcardx are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request. Make sure to follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
