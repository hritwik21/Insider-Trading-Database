## Requirements ##
A virtual environment with the following packages installed : 

* pandas
* os
* selenium
* shutil
* glob

## Usage ##

* Enter the path to the directory (the same one having the python codes) as the download_path
* Download and unpack the chromedriver in the same directory and enter its path in the corresponding variable
* run the "run.py" file using the command 

_python3 run.py_ 

* the final csv file will be saved as "final_data.csv" 
* The same script can be run on a daily basis to update the latest insider trading data


# Creating an SQL database from the data extracted 

_ A single pipeline which runs our code to extract the csv file for Historical or Incremental Insider Trading Database, clean and preprocess it, save a copy locally and by populate the necessary database connected to the MySQL server.
## Requirements ##

The existing virtual environment with the following additional packages installed :

* pyodbc
* LOCAL/ REMOTE CONNECTION TO A MYSQL SERVER

## Usage ##

* Enter the path to the directory (the same one having the python codes) as the download_path
* Download and unpack the chromedriver in the same directory and enter its path in the corresponding variable
* Enter the details and path necessary for the SQL server in the importToSQL.py file
* run the "run.py" file using the command

_python3 run.py_

* After this, the database can be accessed either remotely or locally through SQL queries.

