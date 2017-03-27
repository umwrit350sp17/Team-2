Potential Problems with PDF.js

Specific problems can be reported and reviewed for further assistance 

How to report an issue:

Specify a valid title and provide more details
Ex: Link to issue, screenshot, browser version, operating system, Javascript warning messages
Issues reported without specific details will be closed as invalid/incomplete
It is still possible for corrupted PDF files to be displayed on PDF.js. Report the corrupted file for further help. 


Downloading Oversized Files
  - Build a minified version of the PDF with the command: "Gulp minified"
  - UglifyJS is used to minify JS files because other minifiers could break the PDF.js code. Let it be known that minifiers are safe are safe to use such as Google Closure Compiler, in whitespace/comments removal mode


Files to Avoid 

PDFs with a smaller file size upload faster are more efficient when using this extension. Number of pages does not affect the performance.

1. Avoid using high resolution images -- 150 dpi resolution for scanned images shall be enough for screens, especially for low powered devices;
2. Try to use JPEG encoding for color images/photos in RGB colorspace when possible;
3. Avoid using expensive compositions/effects such as transitions/masking -- flatten transparency;
4. Avoid using PDF generators (or don't create content) that produce ineffective PDF output (e.g. LibreOffice creates a lots of tiny images for vector elements/pictures it does not understand);
5. If there is such a setting, use web-optimized PDF output / linearization;
6. Fix or don't produce corrupted PDFs that do not conform to the PDF32000 specification.

