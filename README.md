# DeNTAS-De-Novo-Transcriptome-Analysis-Statistics

This page contains a basic description of DeNTAS', details of the web design and developent. 

# Web design and development 

1. Index.html: Welcomes users and provides a 'GET STARTED' button to navigate to the next page.
2. About.html: Describes the project mission in a short paragraph.
3. Choose_uploads.html: Lets users define up to three experimental groups and upload files.
4. Upload.html: Uses a Python ‘for loop’ to create a form listing sample names and a dropdown to assign experimental groups, with data collected by Flask for analysis.
5. Results.html: Shows R graphics and a table of significantly expressed genes from the BLAST analysis.

# Cascading Style Sheets (CSS)

CSS controls the presentation of web pages in HTML documents, including fonts, background images, sizes, and colors. It is placed within <style> tags, allowing browsers to apply consistent styles across multiple pages. This improves layout control, simplifies maintenance, and ensures consistency across documents.

# JavaScript and JQuery 

JavaScript is a dynamic, object-oriented language widely supported by web browsers. As an untyped language, it allows variables without type specifications, enabling interactive, executable content within web pages. We introduced user interactivity to our results page using JQuery, a compact JavaScript library, and two plugins, jquery.csvToTable and jquery.tablesorter.dev.js, stored in DeNTAS' ../static/js/ folder. By linking these scripts in the results page header, we enabled the ('#table').CSVToTable() and ('table').tablesorter() functions for dynamic rendering of gene expression tables stored in ../static/results/tables. Additionally, we added a search bar for filtering table rows and a JavaScript alert popup displaying information about R graphics output, created by embedding alert() within <script> tags.


