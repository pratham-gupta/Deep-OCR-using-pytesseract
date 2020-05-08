# Deep-OCR-using-pytesseract
In DMV and other government offices, there is often need of validation of id proofs and certificates. This OCR does the same thing, in this example, OCR extracts text from a registration certificate(RC) of vehice.

We are able to extract registration number of vehicle, Name of the owner, address, mfg. date of vehicle, validity date, Chassis number and engine number. The model can extract text from almost all the different dept RCs as their format are slightly different from each other.

<h3> Original Image </h3>

![1](https://user-images.githubusercontent.com/51241700/81442714-c46d3c00-9191-11ea-989e-58e3718dd291.JPG)


<h3> Proessed Images</h3>

![2](https://user-images.githubusercontent.com/51241700/81442736-cb944a00-9191-11ea-974d-d22e31293021.JPG)
![3](https://user-images.githubusercontent.com/51241700/81442705-bf0ff180-9191-11ea-9872-341a635f8ef9.jpg)

Following processing were performed on images,
1. Rescalling 
2.Bitwise masking 
3.Dialation 
4.Binary thresholding


<h3> Text extracted from image</h3>

CH NO MA3FLEB1S00309631

REG OT > 02/05/2015 OSNO -01

REGN NO : DL2CAU7997

MFG OT : 03/2015 SEATINGC :7 AE

Regular expression can be used to extract required information but RCs of different DMV have different format. If the model is
used for RCs of particular DMV than using Regular Expression is a viable method.
