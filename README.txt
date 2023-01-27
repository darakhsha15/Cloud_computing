================= Performance evaluation of Terapixel rendering in Cloud (Super)computing =================

========= Description =========
This project is about the EDA process of the image rendering on to the cloud.
The code used to perform the analysis is Python Programming Language
The python code is run in Jupyter notebook.

========= Files in Main Project =========
1. Code - 220518655_CSC8634_Cloud_computing.ipynb     --> The code with some explanation in the form of .ipynb to run it later.
2. Code - PDF - 220518655_CSC8634_Cloud_computing.pdf --> The same code in .ipynb in .pdf format for ease of referring.
3. Report - 220518655_CSC8634_Cloud_computing.pdf     --> The Details report of the Analysis
4. Structured Abstract_Key Images - 220518655_CSC8634_structured_abstract --> The Structured Abstract with the Key images which give an outline to the main report.

========= Running the Code =========
1. Download the three .csv files (raw data) using the below given sharepoint link. A proper Newcastle University account is required.
https://newcastle-my.sharepoint.com/personal/nmf47_newcastle_ac_uk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fnmf47%5Fnewcastle%5Fac%5Fuk%2FDocuments%2FTeraScope&ga=1

2. Move the downloaded .csv files into a particular folder and copy the location of the respective files.

3. Open the "Code - 220518655_CSC8634_Cloud_computing.ipynb" file in jupyter Notebook and give the location of the .csv datasets in the python code cell 2. 
   The code looks like below.
   Edit the location between the double quotes ("").

  df_ap = pd.read_csv("application-checkpoints.csv")
  df_gpu = pd.read_csv("gpu.csv")
  df_task = pd.read_csv("task-x-y.csv")

4. In the Jupyter NotebooK options bar select "Cell" and choose "Run All".

5. Now all the code cells will give apropriate outputs.

Further Contribution:
====================
Further Contribution can be done by adding new code or updating the existing "Code - Jashwant Anandan - 220120148.ipynb" file for further analysis 
and following Step 4 from the previous section.



