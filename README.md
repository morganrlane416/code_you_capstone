# code_you_capstone
# KDE Success Data Observations

# Project Setup Instructions

## Prerequisites
Make sure you have the following installed before running the notebooks:
- **Python**: If you are on a mac or linux machine just follow the steps [here](https://www.geeksforgeeks.org/how-to-install-python-on-windows/) to download the newest version of Python. Avoid installing brew as it's not needed and will only complicate things if you're not familiar with the terminal.

- **VS Code**: Follow the installer instructions [here]https://code.visualstudio.com/download. If it prompts you with a survey of development questions, just choose something as it will not change what is installed. Click [here]https://code.visualstudio.com/docs/introvideos/basics to familiarize yourself with VS Code.

- **Jupyter Notebook Extensions for VS Code**: Watch the video [here]https://code.visualstudio.com/docs/datascience/jupyter-notebooks and follow the instructions to add the extensions for Jupyter Notebook in VS Code.

## How to Use
1. Clone this repository.
2. Open the folder in Visual Studio Code.
3. Open the "Capstone" file with the Jupyter extension.
4. Click the "run all" button.

# Project Overview
This project uses data from the KDE report card datasets to provide more insight into connections made between different success metrics. The datasets were cleaned to fit the specific level of interest (high school) and to minimize the amount of unnecessary information being processed. Specifically, the data focused on test scores, quality of school climate/safety, and postsecondary readiness.

Upon running the code in this file, the data should be automatically read, cleaned, and processed. The user will be required to input two integers indicating their content and non-content areas of interest to consider for this topic. 

After providing input, the code should output two scatter plots that show the relationship between the indicated areas of interest. The code then takes other datasets from the original KDE report card source and reads, cleans, and processes them. 

In one dataframe, there are two new columns added to provide specific success metrics to consider in regard to career readiness. In the final task, the code joins and writes a new dataframe that joins all of the pertinent previos dataframes together, so that the information is usable in Tableau for visualization purposes.

To use the data in Tableau, open a Tableau desktop file, add the data source as "together.csv", which is a text file, click on Sheet 1, and select the data of interest to you from the available column/row names. After selecting the data of interest to you, you can choose the visualization that you prefer from the sidebar on the right. Adjust your Tooltips, titles, and features of the visualizations as you see fit.

For details on how the data was originally scored and evaluated, click [here]https://www.education.ky.gov/AA/Acct/Documents/Accountability_at_a_Glance.pdf?utm_source=chatgpt.com. For general information on the available data in regard to KDE report cards, click [here]https://www.education.ky.gov/Open-House/data/Pages/Historical-SRC-Datasets.aspx.

# Technologies Used
Pandas was used to clean and manipulate the dataset to identify trends in Kentucky school data (i.e. test scores, survey results, and postsecondary readiness metrics). Matplotlib was used to show visualizations of the data. SQLite was used to join multiple dataframes into one for the purpose of easier access to information in Tableau. Tableau was used to add more visualizations, specifically in regard to postsecondary readiness.

The project was developed in Jupyter Notebooks to allow for organized code and results associated with the code. 