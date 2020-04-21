# TesseractOCR
Create a simple OCR reader with TessaractOCR.

### Function
Accept the document and output the words into a `.txt` file.

Document formats can be:
- .jpg
- .jpeg
- .PNG
- .pdf

### Interface

For example:
```
python e:/tesseractOCR.py --input=e:/test_pdf.pdf --output=result.text
```

### Pre-processing & post-processing

Pre-processing:

(PDF: convert `.pdf` into `.jpg` first.)

- Convert the image to grayscale
- Apply thresholding or blurring to the image
- Check if the picture needs to be rotated

Post-processing:
- correct the spelling mistake

### Deficiency

- This project can only work great on simple text. If the pdf or image files become more complex, the result will be a mess.
- This project can only deal with one-page pdf file. I didn't work out a good way to accept the pdf file with a lot of pages.


