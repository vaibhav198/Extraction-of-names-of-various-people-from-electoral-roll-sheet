# Extraction-of-names-of-various-people-from-electoral-roll-sheet
# Problem Statement
Write a code to:
  1.Download this PDF
  2.Parse the PDF to extract names
  3.Break the name into initials, first name, last names and middle name(if present)
  4.Put the data systematically in .csv

First of all the pdf file is downloaded and saved. After that texts are extracted from the pdf file. for extracting the text PyPDF2 and textract are used. After extracting the texts, texts are cleaned. A pattern is observed into the text e.g. 'Name:' and then people names and then next will be 'Name:' or "Father's Name" or "Husband's Name". So the basis of this pattern if elif conditions are applied to extract the people name.

# Other Approaches

1. One can also extract the people name with the help of regex.
2. One can also apply OCR to extract the name from the roll sheet, to do this, you need to label it first.
