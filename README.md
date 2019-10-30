# python3-attendance
Reads 3 CSV files and produces list of non-attending adults from the third csv file (SSAttend.csv) who attended in the first csv (SacMtg.csv) but are not listed in the 2nd CSV file (Callings.csv).
Python3 Code: Read in 3 csv files, create sets of names from each, and by finding diff of sets,
produce a list of adult's names present in the first set minus the adult names in the second set 
minus the adult names in the third set. 
The first and third csv files have attendance marked as '1' in date columns when person is present. 
Columns in 1st csv: name, age, attendance (column for each sunday in a quarter with header holding the date). 
2nd Csv : name, organization. 
3rd csv: name, age, attendance (date columns as described in 1st csv)
