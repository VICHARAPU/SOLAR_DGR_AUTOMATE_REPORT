# SOLAR_DGR_AUTOMATE_REPORT
Automation of Daily Generation Report(DGR) from different Monitoring portals or files

# REQUIRMENT
If you are getting Daily generation reports(DGR) in different files like CSV,EXCEL,PDF,WORD and u want to get all files/Sites data into single file but each file is having different table size, column headers, we need to add few columns and other formating in the final table data

# APPROACH FOR THIS PROBLEM ------  I provided the code for this solution in the attached file and u can reffere it
1. We have to use **Python-Pandas Library** to get the solution and it cant be done through Excel-Power query Editor or Power BI because each files are in different format(CSV,EXCEL) and having different table Headers
2. Import Individual file and do the transformation on each file as per your requirment and then retrieve only required columns(Ex: Removing unnecessary columns & rows,Using proper table headers bcz same will be used for further files)
3. Repeate the same step for all files weather it was CSV,EXCEL,PDF,WORD
4. Append all the files by using the same headers in each file
5. Add the conditional columns like caculating Yield,PR,sort the data by Plant Capacity,Colour code for each coumns(Yield,PR) as per your desired values
6. Export the final file into required data files
