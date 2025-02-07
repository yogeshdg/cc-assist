# cc-assist

cc-assist is a command line tool to perform data collection from the postgres tables as well as fetch relavent service logs.This tool has mainly been written to aid in quick log collection for issues related to sda provisioning failures.

The tool mainly does read only operations apart from the pool release functionality that will remove data from the database.This feature has been coded in a very safe way and its a safe operation as well but should be used under BU guidance.This is why it's password protected.
 
**For Escalation/TAC teams:**
This will help to collect logs faster.There is no need to search for commands to collect the logs and the tables.




#**Usage Example:**


This tool needs to be downloaded onto Catalyst Center.  
Easiest way is to use clone the repo 

https_proxy=http://<>:80 git clone https://github.com/yogeshdg/cc-assist


$ ./cc-assist 



*****************************************************************************
*****************************************************************************
*****                                                                   *****
*****                            CC-Assist                              *****
*****                         Version 1.2.0                            *****
*****                                                                   *****
*****************************************************************************
*****************************************************************************


                 Main Menu:
                         1 -> Log Collection 
                         2 -> Utilities 
                         3 -> Exit 
***************************************************************************

        Select an Option : 

## Report and Logs can be found at:
 cc-assist logs will be available in a folder named cc-logs.This folder will be created in the same path where the program lies currently.Depending on the cc-assist option chosen, a sub-folder will be created under cc-logs and the actual logs and tables will be in available as a tar.gz file inside this sub-folder. 

 E.g This is how lan automation log collection folder will look.You need to upload lan_automation_06-24-2024_08-36-21_UTC.tar.gz file to the SR
 cc-logs/lan_automation/lan_automation_06-24-2024_08-36-21_UTC.tar.gz
 
 ## How to submit feedbacks or bugs:
 Please raise an issue in github to report any bugs or submit any new feature asks.In case you feel strongly about the feature ask please submit the code as well.That will increase the chances of that feature getting integrated in cc-assist.Any code you submit should be written in Python 3 only(version 3.6.9 to be precise)
