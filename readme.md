## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install cv2, pdf2image. deskew, scikit-image, pytesseract

```bash
pip install pytesseract
pip install opencv-python
pip install pdf2image
pip install poppler-utils
pip install scikit-image
pip install deskew
```

## Progress:
* pdf to image conversion
* gives text output for normal cases
* detects region with black background
* automatic orientation 


## Findings:
*   for pdf to image conversion dpi must be set
*   so far 120 dpi is showing promising results

## Blockers:
*   does not work when background is not seamless
*   does not work for images
*   does not work for some fonts
*   does not work for graphs 
