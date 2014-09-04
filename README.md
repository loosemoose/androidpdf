androidpdf
==========

Android pdf viewer using pdf.js - https://github.com/mozilla/pdf.js/

To make use of pdf.js this project uses a webview with all the client-side code and markup being served locally.
The client-side files are stored in assets and unpacked and installed within the app's internal storage on start.
PDF files are also local; however this adds some complications with cross-domain origin when trying to load a pdf from a file (file:///). So to workaround it the pdf is injected as base64 encoded data through javascript from the Android activity.

At this point this project serves as a code example on how to make use of pdf.js within an Android webview. It is not meant to be a library. 

Sample pdf files were taken from pdf.js.

