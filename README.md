# BarcodeApiCreator
This is a Delphi / maXbox library for generating barcodes using the https://barcodeapi.org API. The library provides functions to create barcodes of various types, such as QR codes, Aztec codes, Code 39, Code 128, and more. It also allows you to display the generated barcodes in Delphi TImage components.

## Features
Generate barcodes of different types (QR codes, Aztec codes, Code 39, etc.).
Display the generated barcodes in Delphi / maXbox TImage components.
Easy-to-use API integration for barcode generation.
Error handling for network requests and API responses.

<img width="537" height="216" alt="1471_Screenshot2026-03-06190349" src="https://github.com/user-attachments/assets/f1b7d0f7-3548-4ed6-831b-e4bf195136c4" />

## Getting Started
Clone this repository or download the source code.
Add the BarcodeAPILibrary.pas unit to your Delphi project.
Make sure you have the Indy components properly configured in your Delphi IDE.
Use the TBarcodeAPI class to generate and display barcodes in your Delphi application.
Here's an example of how to use the library to display a QR code:

```delphi
uses
  BarcodeAPILibrary;

procedure TForm1.GenerateAndDisplayQRCode;
begin
  TBarcodeAPI.DisplayBarcode('qr', 'Delphifan', Image1);
end;
```

![Barcode Example](https://i.ibb.co/kSTh9Hp/picture.png)

## Dependencies
This library relies on the Indy HTTP component for making requests to the https://barcodeapi.org API. Make sure you have Indy components installed and configured in your Delphi environment. In maXbox we use wininet API.


## License
This library is open source and released under the MIT License. You are free to use, modify, and distribute it as needed. Please check the LICENSE file for more details.

## Contributions
Contributions to this library are welcome. Feel free to open issues, submit pull requests, or suggest improvements. Your feedback and contributions will help make this library even better.

## Issues
If you encounter any issues or have questions related to this library, please open a GitHub issue, and we will do our best to assist you.
