# Automatic_Adjust_Excel_ColumnWidth_Using_Python

In this code, I have used OpenpyExcel Module available in Python, to work on the excel sheet which is already existing.

At first, using the below line, Excel workbook gets loaded.
wb = openpyxl.load_workbook(<Filename with Path>)
  
Then, I have used for loop to operate on multiple sheet, **_if you are working with a single sheet then You can skip the loop._**

Then I traverse through all the columns and adjusted it's width based on the max letter present in a cell.
