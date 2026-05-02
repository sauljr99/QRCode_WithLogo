README.txt
QR Code Generator with Logo

A script I made that generates a QR code for the CSUMB website and
places the CSUMB logo in the center of it. The QR code is red and
white and gets saved as a PNG file. It also pops open automatically
so you can see it right away.

Language: Python
Libraries: qrcode (generates the QR code),
           Pillow / PIL (resizes and pastes the logo onto the QR code)

Notes:
- Install libraries first: pip install qrcode pillow
- Make sure CSUMB.jpg is in the same folder as the script or it will error.
- The logo takes up about 25% of the QR code so it still scans correctly.
- Output is saved as CSUMB.QRCode.png in the same folder.
- You can swap the URL and logo file to make one for any brand.
