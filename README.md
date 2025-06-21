# Acronym Extraction Automation Script

This Python script automatically extracts acronym–full form pairs from `.docx` files using the Schwartz–Hearst algorithm.  
It detects pairs of Acronyms and their full forms, given that the acronyms are enclosed with parentheses `()`.  
It also removes duplicate elements.  
It even finds full forms which might contain line breaks or hyphens.  
Then it basically takes the pair and forms a table-like format and appends all the found pairs to it.  


# Technical Features?

- Handles acronyms in the format: `'Full Form (Acronym)'`  
- Tolerates line breaks and hyphens (e.g., `'Artificial Intel-\nligence'`)  
- Uses first-letter matching to identify accurate expansions  
- Automatically removes duplicates  
- Outputs results in a `.docx` file  


# Requirements:-

- Add your input file to the same directory as the app and you may rename it to `input.docx` or just simply change the actual argument name in the end.  
- Add an empty file to the same directory named `acronym_output.docx`.  


# Installations required:-

- Python  
- `python-docx`  


# Run in terminal:-

```bash
pip install python-docx
python app_name.py
