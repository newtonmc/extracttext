# Extract Text

This bash script uses ImageMagick, tesseract-ocr and xsel to take a screenshot of an area, extract the text from it and copy the extracted text to the clipboard. It is useful for quickly copying text from images or documents into the clipboard for further processing.

## Requirements

- imagemagick
- tesseract-ocr
- xsel

## Usage

Run the script and select the area of the screen to capture. The extracted text will be automatically copied to the clipboard.

## Install

Install requirements
```bash
sudo apt install tesseract-ocr imagemagick xsel
```

Download the last version of script
```bash
wget https://github.com/fberbert/extracttext/releases/download/Latest/extracttext
```

Change script permission to executable
```bash
chmod +x extracttext
```

Move script to PATH bin folder
```bash
sudo mv extracttext /usr/local/bin
```

## Source

https://www.vivaolinux.com.br/artigo/Extracttext-como-extrair-texto-de-uma-area-selecionada-da-tela

## License

This script is licensed under the GPLv3.
