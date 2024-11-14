# Website Overview for DeNTAS :De Novo Transcriptome Analysis & Statistics
Welcome to the DeNTAS project website! This site is designed to provide a user-friendly interface for navigating through various pages related to the software's functionality and resources. It contains essential information about the project, allows users to upload data for analysis, and presents results from bioinformatics processing.

# Website Structure
1. Index.html
Welcome Message: The landing page greets the user and introduces them to the DeNTAS project.
GET STARTED Button: This button directs the user to the next page, helping them move forward in the workflow of using the software.

2. About.html
Project Mission: A short paragraph describing the mission and goals of the DeNTAS project. This page provides essential context to the user about the project’s purpose and the software's capabilities.

3. Choose_uploads.html
Experimental Group Input: This page allows users to specify the experimental groups for their data (from 2 to 4 groups).
File Upload: After selecting the appropriate number of experimental groups, users can browse their files and upload them for further processing.

4. Upload.html
Form for Sample Information: Using a Python "for loop," this page dynamically fills a form with the names of the uploaded samples and offers a dropdown menu to select the corresponding experimental group for each sample.
Data Submission: Once the form is filled, the information is sent to Flask, which processes the data and feeds it into the data analysis pipeline.

5. Results.html
R Graphics Output: This page displays the output of R-based analyses, including visualizations like graphs generated from the data.
BLAST Results: A table is shown with the significantly expressed genes identified by the BLAST analysis, giving users detailed insights into their experimental data.

# How to Use the Website
1. Start at the 'Index.html': Click on the ‘GET STARTED’ button to begin.
2. Provide Project Details: Use the 'About.html' to familiarize yourself with the project’s mission.
3. Upload Your Data: In 'Choose_uploads.html,' select the number of experimental groups and upload your files.
4. Fill in Sample Information: On 'Upload.html,' enter your sample names and select the experimental group for each.
5. View Your Results: Finally, in 'Results.html,' you will see the graphical output and a table summarizing the significant results from your analysis.
