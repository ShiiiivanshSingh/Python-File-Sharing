﻿#  LOCAL FILE SHARING USING PYTHON

This project sets up a basic HTTP server using Python and generates a QR code for accessing the server locally. The server serves files from a specified directory (in this case your default `Downloads` folder), and the QR code provides an easy way to access the server URL.

Here is the link to the website: [LINK](https://bit.ly/3zzYbEJ)

## How It Works

1. **HTTP Server**: The script sets up an HTTP server on port `8010`.
2. **QR Code Generation**: Generates a QR code containing the server's local IP address and port.
3. **Displaying Information**: The server information and QR code are displayed in the terminal.

## Usage

To use this project, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/ShiiiivanshSingh/Python-File-Sharing
    ```

2. **Navigate to the Project Directory**:
    ```sh
    cd Python-File-Sharing
    ```

3. **Run the Script**:
    ```sh
    python RUN.py
    ```

4. **Access the Server**: 
   - Open the generated QR code image `myqr.svg` with a QR code reader or 
   - Visit the displayed URL in your browser.

5. **File Placement**: 
   - Place the files to be shared in your default `Downloads` folder.
   - The files present in the directory will be displayed in the interface.

## Requirements

- Python 3.2
- `pyqrcode`
- `python3-png` (for PNG support)

```sh
pip install pypng
```

```sh
pip install pyqrcode
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## By Shivansh Pratap Singh
 (You can always check out my socials at : https://linktr.ee/ShivanshPratapSingh)

Made On 10.09.24 <3
