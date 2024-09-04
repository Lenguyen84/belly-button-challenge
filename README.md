BELLY BUTTON BIODIVERSITY DASHBOARD
1.	Project Overview and Purpose: This exercise aims to create an interactive dashboard for exploring the Belly Button Biodiversity dataset, which catalogs the microbes that inhabit human navels.

2.	 Dataset Description and preprocessing: The Belly Button Biodiversity project is conducted by a laboratory at North Carolina State University. More details can be found at this website. The dataset reveals that a small number of microbial species, known as operational taxonomic units (OTUs), were found in more than 70% of individuals, while the rest were relatively rare. The dataset is available in JSON format here.
Functions were developed to: (a) filter metadata and append new tags for each key-value pair in the filtered metadata, (b) generate charts for the dashboard, and (c) execute these tasks upon page load.	

3.	 Results and Analysis:
The user can select a Test Subject ID Number, which will display the Test Subject's demographic information in a table, their Top 10 Bacteria Cultures Found in a bar chart, and a bubble chart showing the quantity of each type of bacteria found. 

![Image](<Belly Button Biodiversity Dashboard.png>)

This dataset should be treated as sensitive. Although patient names are not included, the available information (e.g., date of birth, gender, location) may be sufficient to identify individuals. Access should be restricted in accordance with the guidelines outlined in the Health Insurance Portability and Accountability Act

4.	Instructions for Interacting with the Project
.	The JavaScript code is located in the static/js folder under the file name "app_Le.js."
.	The index file is located in the main folder as "index.html."
.	The dataset samples.json." is available as a .json file in the main folder 
.	A screenshot of the website is saved in the main folder as “Belly Button Biodiversity Dashboard.png.”

5.	References:
.	Xpert Learning Assistant
.	https://plotly.com/javascript/horizontal-bar-charts/
