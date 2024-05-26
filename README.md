# everyday_scripts
just to make everyday tasks a bit easier

📄 PDF Extraction Script
Overview
Use to extract specific pages from a PDF document and save them as a new PDF file.
Use to make excerpts from larger documents or extract specific pages to study.
Script adjusts for any offset between PDF's internal page numbers and the printed page numbers in the book, if there are any discrepancies.

🛠 Prerequisites
Python 3.x: Make sure Python 3.x is installed on your system.
PyPDF2: Install the PyPDF2 library by running:
'pip install PyPDF2'

🚀 Usage
Use the following command to run the script:
'python3 pdf_solution.py <input_pdf_path> <output_pdf_path> <start_book_page> <end_book_page> <offset>'

Arguments
<input_pdf_path>: Path to the input PDF file.
<output_pdf_path>: Path where the output PDF file will be saved.
<start_book_page>: Starting page number in the book.
<end_book_page>: Ending page number in the book.
<offset>: Difference between the PDF's internal page numbers and the book's printed page numbers.

📚 Example usage
To extract book pages 96 to 100 from academic_book.pdf and save them to chapter_7.pdf, with an offset of 2 (where PDF page 102 corresponds to book page 100), use:
'python3 pdf_solution.py path_to_academic_book.pdf path_to_chapter_7.pdf 96 100 2'

