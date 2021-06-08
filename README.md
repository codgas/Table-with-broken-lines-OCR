# Table-with-broken-lines-OCR
## This a Python notebook to detect a table and extract it from a scanned pdf or image

For scanned documents, especially old ones, some table lines can broken, and that can be very hard for typical  table OCR libraries to read!
in this repository I deal with issue, by first detecting the table using layout parser library, then preform OCR on all the document , detect the contours and cells of the table, and finally assign the texts using their coordinates to their respective cells.I found that this method works much better then applying OCR to each detected contour cell
