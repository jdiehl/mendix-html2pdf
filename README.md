# Mendix Module - HTML2PDF

This module provides a JS Action that converts an HTML Container into a downloadable PDF.

## Usage

1. Create a Nanoflow
2. Add the MakePDF Action
3. Configure the Action:
   
   Target: The class of the container that should be converted into a PDF (must be unique!)
   Filename: The filename used for the downlaoded PDF
   Scale: scale factor for the PDF (larger is bigger)
   Orientation: Landscape or Portrait

## Notes

The module uses [jsPDF](https://github.com/MrRio/jsPDF) and [HTML2Canvas](https://html2canvas.hertzen.com).
