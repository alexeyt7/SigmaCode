# SigmaCode
This repository contains the code for workshops and stickers at SigmaCamp. The code is written in Python, and primarily generates LaTeX documents to be printed and used around camp. Additionally, the sticker code uses the Google Sheets API to write to and read from online spreadsheets.

This code serves two main functions:
- Generate stickers for SigmaStaff using information stored in the Master spreadsheet
- Assign campers to workshops based on their preferences and generate documents with information on workshops

Currently, work is being done to better automate these tasks and expand the degree of automation to save as much time as possible and reduce possible error.

In order to make code as maintainable as possible, code is formatted as follows:
- Use [docstrings](https://www.geeksforgeeks.org/python-docstrings/) whenever possible to make functions as understandable as possible
- Name files in camelCase without abbreviations (workshop instead of wshop)
- Apply [black](https://black.readthedocs.io/en/stable/index.html) to all files, configuration for [pre-commit](https://pre-commit.com/) is provided
