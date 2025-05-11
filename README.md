# Bifurcator - PDF Scan Processor

## Overview

Bifurcator is a browser-based tool for processing PDF scans with specialized features for handling book scans. It allows users to split pages in half (useful for book spreads) and reorder them in a reader-friendly sequence.

## Features

- **PDF Page Splitting**: Automatically split each page into left and right halves, ideal for book scans
- **Page Reordering**: Arrange split pages in a natural reading order
- **Page Selection**: Choose specific pages to process (all, none, odd, or even)
- **Mobile-Friendly UI**: Responsive design works on various devices
- **Client-Side Processing**: All processing happens in your browser, no data is sent to any server

## Use Cases

- **Book Digitization**: Process book scans where two pages appear on a single PDF page
- **Magazine Processing**: Split magazine spreads into individual pages
- **Document Reorganization**: Select and reorder specific pages from longer documents

## How to Use

1. **Upload a PDF**: Click the upload button to select a PDF file from your device
2. **Preview Pages**: Review the pages that will be processed
3. **Select Pages**: Use the selection tools to choose which pages to include
4. **Choose Options**:
   - **Split Pages**: Toggle to split each page into left and right halves
   - **Reorder Pages**: Interleave pages in reading order (recommended for books)
5. **Process**: Click "Process PDF" to generate the new document
6. **Download**: Save the processed PDF to your device

## Technical Details

Bifurcator uses the following libraries:
- PDF.js for rendering and analyzing PDF documents
- jsPDF for creating new PDF files
- HTML5 Canvas for image manipulation

## Browser Compatibility

Works with modern browsers including:
- Chrome/Edge (latest versions)
- Firefox (latest versions)
- Safari (latest versions)

## Limitations

- Very large PDF files may cause performance issues depending on your device
- Complex PDFs with non-standard formatting might not split perfectly

## Privacy

Bifurcator processes all files locally in your browser. No data is uploaded to any server, ensuring your documents remain private and secure.
