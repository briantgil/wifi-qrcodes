# WiFi QR Code
### QR code definition for WiFi connection string:

WIFI:S:< SSID >;T:< WPA|WEP >;P:< password >;[H:< true|false| >];

***Help:***
 - S: SSID or network name 
 - T: security/encription type (WEP is deprecated) 
 - P: network password 
 - H: hidden network (optional, but must include trailing semicolon [";"])

### Steps to build QR code
1. Use a QR Code Generator site such as: [QR Code Generator | Create Your Free QR Codes (qr-code-generator.com)](https://www.qr-code-generator.com/) 
2. Generate QR Code:
    1. Choose text type and enter the WIFI string replaced with your connection information
    2. Or Choose WIFI type, enter WIFI connection information, and click GENERATE QR CODE
