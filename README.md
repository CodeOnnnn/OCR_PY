# ImageReader
This website is able to read all the text written in an image using OCR (Optical Character Recognition).
It uses Flask (back-end) and as front-end framework Material Design Bootstrap (jQuery edition).

# Setup
## Install requirements

### Windows
```bash
pip install -r requirements.txt
```

## Setup Tesseract path
Insert Tesseract file path in main.py (line 54):

```python
# Example: r'D:\TesseractOCR\tesseract'
pytesseract.pytesseract.tesseract_cmd = r'<path_to_tesseract_exe>'
```

## Windows
```bash
python main.py
```
