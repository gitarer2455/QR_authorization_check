# QR Code Scanner & Access Control Automation

This is a simple Python automation tool leveraging **computer vision** to distinguish between authorized and unauthorized individuals (e.g., employees or students) based on digital QR IDs. The tool can verify access rights and also convert any QR code into a website link, providing relevant product information.

## Key Features

- **QR Code Scanning and Validation**: Scan QR codes to validate if the individual is authorized to access a specific area.
- **Digital ID for Access Control**: Ensure that only authorized personnel are allowed entry using their digital QR ID.
- **QR Code to URL**: Convert any QR code into a website link, allowing easy access to linked content or product details.
- **Product Information Retrieval**: Extract product information associated with the QR code, making it easy to track and display relevant data.

## How It Works

1. **Scan QR Code**: The tool scans QR codes using a camera, either for an access ID or product-related QR code.
2. **Validate Access**: After scanning, the tool checks if the QR code belongs to an authorized individual.
3. **Decode QR Data**: The QR code's data is decoded to either validate access or retrieve a URL/product details.
4. **Display Information**: If the QR code links to a product, the tool retrieves and displays the associated information.

## Built With 💻

- **OpenCV**: Used for computer vision tasks, such as capturing and processing QR codes.
- **NumPy**: A library used for numerical data processing, useful during QR code validation.
- **pyzbar**: A Python library that decodes QR codes, enabling the scanning functionality.

## Why This Project?

This tool is ideal for building secure access control systems or for quickly converting and extracting data from QR codes. Whether you're securing a building or managing product details, this tool provides an easy-to-use solution for QR code-based tasks.

## Installation

To get started with the QR code scanner and automation tool, follow these steps:

```bash
git clone https://github.com/gitarer2455/QR_authorization_check
cd Auth_detector
pip install -r requirements.txt
python Qrscan.py 
