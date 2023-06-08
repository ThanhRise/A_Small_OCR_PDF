# A_Small_OCR_PDF

- Install dependencies

```
tesseract 4.x
opencv
filetype
fitz
```

- Run program
``
python pdf2text.py
``


```
usage: pdf_ocr.py [-h] -i INPUT_PATH [-a {Highlight,Redact}] [-s SEARCH_STR] [-p PAGES] [-g GENERATE_OUTPUT]

Available Options

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT_PATH, --input_path INPUT_PATH
                        Enter the path of the file or the folder to process
  -a {Highlight,Redact}, --action {Highlight,Redact}
                        Choose to highlight or to redact
  -s SEARCH_STR, --search_str SEARCH_STR
                        Enter a valid search string
  -p PAGES, --pages PAGES
                        Enter the pages to consider e.g.: (0,1)
  -g GENERATE_OUTPUT, --generate_output GENERATE_OUTPUT
                        Generate content in a CSV file

```
