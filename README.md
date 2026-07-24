# Source-to-Notes-Prototype

## Project Overview

This project is a prototype of a Source-to-Notes workflow developed as part of an Agentic AI learning project. The goal is to transform a research paper into structured, claim-level research notes while demonstrating reproducibility, validation, and human review.

The input is a research paper in PDF format, and the output is a structured CSV containing research notes with supporting evidence.

---

## Project Workflow

1. Read a research paper (PDF).
2. Extract text from each page using Python.
3. Create structured claim-level research notes.
4. Store the notes in a pandas DataFrame.
5. Validate that each evidence snippet matches the correct page.
6. Save the notes as a CSV file.
7. Read the CSV back into pandas to verify the output.
8. Complete a final human review.

---

## Files Included

- **Week4_Source_to_Notes.ipynb** – Main Jupyter Notebook containing the workflow.
- **ten_simple_rules.pdf** – Research paper used as the source document.
- **sample_notes.csv** – Initial sample notes.
- **checked_notes.csv** – Output from the basic checker.
- **source_to_notes_v0_1.csv** – Final structured research notes.

---

## Technologies Used

- Python
- pandas
- pypdf
- Jupyter Notebook
- GitHub

---

## Automated Tasks

The following tasks are automated:

- Extracting text from the PDF
- Organizing notes with pandas
- Validating page numbers and evidence snippets
- Saving structured notes to CSV
- Reading the CSV back into pandas for verification

---

## Manual Tasks

Because OpenAI API access was not available, the following tasks were completed manually:

- Generating structured research notes using ChatGPT
- Reviewing each claim against the original paper
- Approving or correcting the final notes

---

## Future Improvements

The next improvement would be to integrate the OpenAI API so the notebook can automatically generate structured research notes directly from the extracted PDF text. This would create a fully automated Source-to-Notes workflow while keeping the final human review step.

---

## Author

**Brian Kinyua**  
