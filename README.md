# MediScan
For helping medical field, we have created a project in which it will scan the uploaded image and using tesseract OCR by google, then transferring that stored data into any storage. Here, we have used excel file.

# Image Processing and Data Extraction

This Streamlit app allows users to upload an image containing information such as patient name, contact, address, and date, and extract that information using OCR (Optical Character Recognition). The extracted information is displayed on the web interface and saved to an Excel file.

## Features

- Upload an image (JPEG, PNG, or JPG format) containing information.
- Extract patient name, contact, address, and date from the uploaded image using OCR.
- Display the extracted information on the web interface.
- Save the extracted information to an Excel file.
- Download the Excel file containing the extracted information.

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Streamlit app using `streamlit run app.py`.
4. Upload an image containing information using the file upload widget.
5. View the extracted information displayed on the web interface.
6. Download the Excel file containing the extracted information using the provided link.

## Dependencies

- Streamlit
- OpenCV (cv2)
- Pytesseract
- Openpyxl
- Numpy
- ossaudiodev (optional, if used in the future)

## Author

Lakshya Jain, Karan Gupta

## License

This project is licensed under the [MIT License](LICENSE).
