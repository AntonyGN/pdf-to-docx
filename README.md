# PDF to DOCX Converter
This is a simple Python script that can convert PDF files to DOCX format using the PyPDF2 and python-docx libraries. It can be used with Jupyter Notebook to convert PDF files on your local machine.

## Getting Started
Clone the repository:
```bash
git clone https://github.com/AntonyGN/pdf-to-docx.git
```
Install the required Python libraries:
```bash
pip install PyPDF2 python-docx
```
Start Jupyter Notebook:
```bash
jupyter notebook
```
Open the ```pdf-to-docx.ipynb``` notebook in Jupyter.

## Usage
1. Place the PDF file that you want to convert in the same directory as the ```pdf-to-docx.ipynb``` notebook.
2. In the first cell of the notebook, update the filename to match the name of your PDF file:

```bash
filename = 'your pdf name.pdf'
```

3. Run the notebook cells by clicking on each cell and pressing ```Shift + Enter```.
4. The converted DOCX file will be saved in the same directory as the PDF file with the same filename, but with the ```.docx``` extension.

## Limitations
- This script only works with PDF files that contain text. If your PDF file contains images or other non-text elements, you may need to use a different approach.
- This script only converts one PDF file at a time. If you need to convert multiple PDF files, you will need to run the script for each file separately.

## Contributing
If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request.

