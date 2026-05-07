# Project5
# Project Summary
Client: Garrison Diversion Project and Red River Valley Water Supply Project (RRVWSP)
The client is studying a proposed pipeline system that moves water from Lake Sakakawea through the McClusky Canal, and moves into the Sheyenne River and eventually Lake Ashtabula. The client wants to better understand if the water quality will degrade as it moves downstream through the canal. They want to know if the water mixing in the Sheyenne River will negatively impact Lake Ashtabula. 
The main goal of this project was to analyze the water quality using Python tools. The project listed the major cations, anions, total dissolved solids (TDS), hardness, temperature, and pH. A statistics summary, four boxplots, and a mixing model were all created in the code. 
The final output of this project is a complete Python notebook that organizes all the data, calculates statistics, creates visualizations, a interactive graph using Altair, and solved mass balance equations. The client requested a dynamic TDS mixing model which is also included in the code.
This project has a repeatable and organized workflow forp any future water quality evaluations. 

# Manual

Under the files in this directory, a file named "AbdiSpeth_Project5_Code.ipynb" contains the final code analysis. 

# Steps to use code in Jupyter Notebook
1. Open the listed code from the repository.
2. Download the file.
3. Open terminal.
4. Run the command: "jupyter notebook".
5. Click the upload button in the top right.
6. Find the downloaded file and upload it.
7. Upload the csv files used in the code
   "CIVE202_Project5_RRVWSP(in).csv"
   "List of USGS Canal Locations(Sheet1).csv"
8. Run each code cell from top to bottom.
9. The notebook will automatically run all the code.

# Steps to use code in another interpreter
1. Open the listed code from repository.
2. Copy the code from the notebook.
3. Open another interpreter.
4. Paste the code into the interpreters code.
5. Put csv files in the same directory as code.
6. Install any necessary packages.
7. Run the code from top to bottom.
8. The notebook will automatically run the code. 

# Water Quality Parameters
Major Cations:
1. Calcium
2. Magnesium
3. Sodium
4. Sodium Absorption Ratio

Major Anions:
1. Chloride
2. Sulfate
3. Carbonate
4. Bicarbonate

Other:
1. Total Dissolved Solids
2. Temperature
3. pH
4. Hardness

# TDS Mixing Model
The project using the following equation:
Q_pipe C_pipe + Q_Sheyenne C_Sheyenne = Q_Ashtabula C_Ashtabula
This allows for the user to test multiple scenarios. 

# Contributors
Ayub Abdi
Eli Speth
