OCR PDFs directly in your browser

This tool runs entirely in your browser. No files are uploaded to a server.

It uses Tesseract.js for OCR and PDF.js to convert PDFs into text.

Originally from [simonw/tools](https://github.com/simonw/tools/blob/main/ocr.html). Modified by Jurjen de Vries to compile all PDF pages into a single text file without using images. The invoice data from the PDF will be submitted to a Cloudflare worker for analysis and processing by a large language model (LLM) and then sent to the Bunni bookkeeping API.
