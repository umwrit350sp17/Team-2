Frequently Asked Questions

*This is a modified and special selected FAQ due to the specificity of this project. For further potential questions please see the original FAQ at: https://github.com/mozilla/pdf.js/wiki/Frequently-Asked-Questions


Is it possible to add annotations to a PDF?

-PDF.js is mainly written for reading PDF files, not editing them. Because of that we don't yet support adding any kind of annotations. We do however support rendering a number of annotation types for viewing.

PDF.js does not render my files correctly. Can I report an issue?

-Yes. The issues are used to track both bugs filed by users and specific work items for developers. Try to file one issue per problem observed.

-Please specify valid title (e.g. "Glyph spacing is incorrect" instead of "PDF.js does not work") and provide more details about the issue: link to the PDF, location in the PDF, screenshot, browser version, operating system, PDF.js version and JavaScript console warning/error messages. The issues that do not have enough details provided will be closed as invalid/incomplete.

The PDF.js files are too big. Is it possible to obtain minified versions of the JS files?

-You can build a minified version of PDF.js using the following command:

-"gulp minified"

-We use UglifyJS to minify the JS files. It is known that other minifiers might break PDF.js code if advanced options are used (see #710 or #2479). It's safe to use minifiers, such as Google Closure Compiler, in whitespace/comments removal mode.

What are the PDF.js keyboard shortcuts?


-Navigation

next page: n, j, right arrow key, click in presentation mode
previous page: p, k, left arrow key, Shift + click in presentation mode
The home, end, page up, page down and all arrow keys can be used to navigate the document.

-Viewer controls

User interface buttons or ctrl + mouse wheel can be used to change the zooming level, but keyboard shortcuts are also available:

zoom in: ctrl + +, ctrl + =
zoom out: ctrl + -
restore normal zoom: ctrl + 0
rotate the document clockwise: r
rotate counterclockwise: shift + r
presentation mode: ctrl + alt + p (does not work in IE11)
toggle hand tool: h
move focus to the 'go to page' box: ctrl + alt + g
(replace ctrl with meta on some configurations)

-Outline sidebar

After showing the sidebar, click on the "Show document outline" button (Show document outline) to show the document outline (if the PDF file has one).
Nested outline items can be expanded/collapsed by clicking on the triangles at the left of an item.
To expand/collapse all items under the selected item, press Shift while clicking on the triangle.
Double-click on the "Show document outline" button (Show document outline) to expand/collapse all outline items.



