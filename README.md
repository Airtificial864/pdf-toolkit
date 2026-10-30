# PDF Toolkit

Merge, split, reorder, rotate and extract PDF pages **entirely in your browser**.
Your files never leave your computer — nothing is uploaded to any server.

## Features
- Drag & drop PDFs, JPG and PNG images (images become PDF pages)
- Visual page grid with thumbnails and a zoom slider
- Drag to reorder pages, even across different documents
- Merge all pages or only the selected ones
- Extract selected pages into a new PDF
- Split by range (e.g. `1-3, 7, 10-12`) or every N pages (downloaded as a `.zip`)
- Rotate, duplicate and delete pages
- Optional footer page numbers and reverse page order
- Undo (`Ctrl+Z`), select all (`Ctrl+A`), delete (`Delete`)
- Clear errors for password-protected or damaged PDFs

## Usage
No build step needed. Either:
1. Open `index.html` in any modern browser, or
2. Use the hosted version via GitHub Pages (Settings → Pages → Deploy from branch `main`).

## Built with
- [pdf-lib](https://pdf-lib.js.org/) – creating and editing PDFs
- [pdf.js](https://mozilla.github.io/pdf.js/) – page previews
- [JSZip](https://stuk.github.io/jszip/) – bundling split files

Libraries load from cdnjs, so an internet connection is needed on first load.

## Contributing
Issues and pull requests are welcome. Ideas: compression, page cropping, watermarking, dark mode.

## License
[MIT](LICENSE)
