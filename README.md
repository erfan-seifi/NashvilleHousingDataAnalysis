# Nashville Housing Data Analysis utilizing SQL

In case of having error code 2068 while importing the csv data into NashvilleHousing table in MySQLWorkbench, run the following command on your terminal: "mysql --local-infile=1 -u your_username -p" to enable access to the file and edit the server connection string in MySQL workbench by navigating to Home, then: Edit Connection > Advanced > Copy OPT_LOCAL_INFILE=1 into Others box on a new line.
