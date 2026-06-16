# QR Code Generator

A simple web-based **QR Code Generator** built using **Python Flask**. This application allows users to generate QR codes from text, URLs, or any input data and download them instantly as PNG images.

## Features

* Generate QR codes from user input
* Download QR codes as PNG files
* Simple and user-friendly interface
* In-memory image processing using `BytesIO`
* Lightweight and easy to deploy
* Compatible with multiple Flask versions

## Technologies Used

* Python
* Flask
* QRCode Library
* HTML/CSS
* BytesIO

## Project Structure

```
QR-Code-Generator/
├── app.py
├── templates/
│   └── index.html
├── static/
│   ├── style.css
│   └── script.js
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/QR-Code-Generator.git
   cd QR-Code-Generator
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python app.py
   ```

4. Open your browser and visit:

   ```
   http://127.0.0.1:5000
   ```

## Usage

1. Enter text, a URL, or any data into the input field.
2. Click the **Generate QR Code** button.
3. The application creates the QR code instantly.
4. Download the generated QR code as a PNG image.

## Future Enhancements

* QR code customization (colors and logos)
* Support for multiple image formats
* QR code preview before download
* QR code history and storage
* Mobile-friendly enhancements

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

---
If you found this project useful, consider giving it a star on GitHub!
