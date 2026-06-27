====================================
  REKLA RECEIPT GENERATOR
  README / HOW TO USE
====================================

WHAT IS THIS?
-------------
This tool lets you upload your Rekla registration CSV export
and download all receipts as a single PDF file — instantly.
No installation needed. Works on Windows with Chrome or Edge.


HOW TO USE
----------
1. Double-click "ReklaReceiptGenerator.html"
   → It opens in your browser (Chrome or Edge)

2. Click "Upload CSV File" (or drag and drop your file)
   → Select the CSV file exported from your Rekla system

3. Use the filter buttons to select:
   → "All"       — generate receipts for everyone
   → "PAID only" — generate receipts for paid entries only
   → "PENDING"   — generate receipts for pending entries only

4. Check the preview table to make sure data looks correct

5. Click "⬇ Download All as PDF"
   → Wait for the progress bar to finish
   → PDF is saved to your Downloads folder automatically


CSV FILE FORMAT
---------------
Your CSV must be the standard Rekla export with these columns:

  Entry ID, Event, Category, Seat No, Coupon Code,
  Member 1 Name, Member 1 ID, Member 1 Mobile, Member 1 Location,
  Member 2 Name, Member 2 ID, Member 2 Mobile, Member 2 Location,
  Payment Status, Payment Method, Transaction Ref, Date

If Member 2 is not present, leave those columns blank or set to N/A.


INTERNET REQUIREMENT
--------------------
The tool needs internet ONLY the first time you open it
(to load the PDF library from the internet).
After that first load, it works offline.

To use fully offline: open the file once while connected to
the internet, then it will work without internet after that.


TROUBLESHOOTING
---------------
Problem : PDF downloads but text shows as boxes
Solution: Open the file in Google Chrome (not Edge)

Problem : "Missing columns" error
Solution: Make sure you export directly from Rekla without
          modifying the column headers

Problem : File not uploading
Solution: Make sure the file is saved as .csv or .tsv
          (not .xlsx or .xls)

Problem : Page is blank
Solution: Right-click the HTML file → Open with → Google Chrome


FILES IN THIS FOLDER
--------------------
  ReklaReceiptGenerator.html  ← The app (open this)
  sample_data.csv             ← Sample data to test with
  README.txt                  ← This file


SUPPORT
-------
NAMADHU REKLA helpline number

====================================
