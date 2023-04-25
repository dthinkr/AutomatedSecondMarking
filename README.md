# AutomatedSecondMarking
A script to validate the total marks of annotated PDF files and add a green checkmark overlay to the first page if the check passes.

## Requirements

- Python 3.6 or higher
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [reportlab](https://pypi.org/project/reportlab/)
- [pdf2image](https://pypi.org/project/pdf2image/)
- [Pillow (PIL fork)](https://pypi.org/project/Pillow/)

To install the required libraries, run:

```bash
pip install PyPDF2 reportlab pdf2image Pillow
