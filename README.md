This is a small python program that will take an excel spreadsheet and convert it into a CSV file(s). For each tab of the spreadsheet, 
a file will be created along with the tabs name.

Requires the following be installed:
pip install openpyxl

Usage: 
python xls2csv spreadsheet.xlsx

Example:

(ACI) C:\Users\stturnbu\Documents\+++Programming>python xls2csv.py "ACI OOB.xlsx
Export DC3 - Script ...
 ... done
Export DC2 - Script ...
 ... done
Export DCI - Script ...
 ... done
Export DCI ...
 ... done
Export DC2 ...
 ... done
Export DC3 ...
 ... done

Output:

DC2 - Script.csv
DC2.csv
DC3 - Script.csv
DC3.csv
DCI - Script.csv
DCI.csv
