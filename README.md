# PDF to Excel Converter

## Overview
This web application allows users to upload multiple PDF files and convert each PDF into an individual Excel (.xlsx) file. It is designed to extract table-like structures from PDF pages and export the data into Excel spreadsheets. The app uses PDF.js to parse PDF content and SheetJS (xlsx) to generate Excel files directly in the browser, requiring no server-side processing.

## Setup
1. Download the `index.html` file.
2. Open the `index.html` file in a modern web browser (Chrome, Firefox, Edge).
3. No additional installation or server setup is required.

## Usage
1. Click the dashed upload area or drag & drop one or more PDF files onto it.
2. After selecting files, the "Convert to Excel" button will become enabled.
3. Click the "Convert to Excel" button to start the conversion process.
4. The app will process each PDF, extract table data, and automatically download an Excel file for each PDF.
5. Conversion logs and status messages appear below the button for user feedback.

## Features
- Supports multiple PDF file uploads at once.
- Drag & drop or file selection interface.
- Extracts text from PDF pages and attempts to parse table structures by grouping text lines.
- Converts extracted tables into Excel spreadsheets (.xlsx).
- Downloads each converted Excel file individually.
- Runs entirely client-side with no server dependency.
- Accessible keyboard navigation and screen reader friendly status updates.
- Uses popular open-source libraries PDF.js and SheetJS.

```