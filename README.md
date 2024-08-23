# Barcode and QR code Generator
Serving barcode and QR code using Python and Flask web framework

This is a random, short and simple Python and Flask web framework codes that might come in handy.
I will also try extend this simple example and look for simple use cases where we can implement it..

I just want to share my experience and adventure while I'm learning Python and other frameworks

# Flask

Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. It has no database abstraction layer, form validation, or  any other components where pre-existing third-party libraries provide common functions.

# Barcode types

- EAN8
- EAN13
- EAN5
- ISBN
- UPCA
- QR
- Code128
- Code128Auto
- Standard39
- Standard93
- MSI
- Codebar
- Code11
- FIM
- POSTNET
- Extended39
- Extended93
- I2of5
- ECC200DataMatrix


>   **EAN13** European Article Numbering System (EAN) is a superset of
> U.P.C. EAN-13 consists of 13 numbers.
> 
>   **UPCA** UPC (technically refers to UPC-A) consists of 12 numeric
> digits
> 
>   **Code 39 or Standard39** specification defines 43 characters,
> consisting of uppercase letters (A through Z), numeric digits (0
> through 9) and a number of special characters (-, ., $, /, +, %, and
> space)
> 
>   **Code128** is a high-density linear barcode symbology. It is used
> for alphanumeric or numeric-only barcodes. It can encode all 128
> characters of ASCII and, by use of an extension symbol (FNC4), the
> Latin-1 characters defined in ISO/IEC 8859-1.
> 
>   **Code 93 or Standard93** character set consists of barcode symbols
> representing characters 0-9, A-Z, the space character and the
> following symbols: /, + , %, - , . , $ .
> 
>   **Code11** can encode any length string consisting of the digits 0–9
> and the dash character (-).
> 
>   **MSI** bar code represents only digits 0–9; it does not support
> letters or symbols.
> 
>   **QR** codes are 2D matrix barcodes with a strong consumer focus,
> often used in tracking and marketing such as advertisements,
> magazines, and business cards. Free to use, flexible in size, have a
> high fault tolerance, and have fast readability, though they can’t be
> read with a laser scanner. QR codes support four different modes of
> data: numeric, alphanumeric, byte/binary, and Kanji. QR code growth
> began in Japan and use continues to grow today. They are public domain
> and free to use.
> 
> **Datamatrix or ECC200DataMatrix** codes are 2D barcodes used to label small items, goods, and documents. Their tiny footprint makes them
> ideal for small products in logistics and operations. In fact, the US
> Electronic Industries Alliance (EIA) recommends that they be used to
> label small electronic components. Similar to QR codes, they have high
> fault tolerance and fast readability.


# Additional readings

- https://docs.reportlab.com/reportlab/userguide/ch1_intro/ 
- https://docs.reportlab.com/reportlab/barcode/ 
- https://flask.palletsprojects.com/

