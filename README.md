# DataScience Journal
This repository contains notes and tutorials on how I use Python to explore, clean, validate, and analyze data.

### [Validate Sample Sheet](VerifyCSV.ipynb)

This is an example of validating the data that will be included in an [Illumina sequencing sample sheet](https://www.illumina.com/content/dam/illumina-marketing/documents/products/technotes/sequencing-sheet-format-specifications-technical-note-970-2017-004.pdf).  I was asked to ensure that:

- All sample names are unique
- Sample names follow formatting guidelines.
  - No more than 100 characters in length
  - Include only alpha-numeric characters or dashes (-)
- Sample names start with the Raw Sample names
