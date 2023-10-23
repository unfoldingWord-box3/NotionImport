# NotionImport
Toolchain to preprocess google docs for import into Notion

The Notion import tool is quite fragile and does not support many file formats. 
uW Google docs have some unsupported formats
This package converts google docs to files that Notion imports

## Usage
- Download your google docs
- Unzip the downloaded files into a folder like: sharedTraining
- Place the following tools into the folder containing your extracted files
- run rfn to preprocess the files
     sh ./ppg sharedTraining
- Follow the instructions at the end of the program
  
## Tool Roles
rfn - Refactor File Names to retain folder structure
pdf2html - convert PDFs to HTML
ppg - PreProcess Google docs for Notion Import
ppt2md - Convert PPTX files to Markdown

## Requirements
### For windows 
You will need root password to install these: 
- Bash or WSL for execution environment
- soffice for Libre Office cli conversion of ODT documents to DOCX
### windows and linux
These will be auto installed but you will still need root password 
- zip
- pptx2md
