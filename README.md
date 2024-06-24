# cc-assist

cc-assist is a command line tool to perform data collection from the postgres tables as well as fetch relavent service logs.This tool has mainly been written to aid in quick log collection for issues related to sda provisioning failures.

The tool mainly does read only operations apart from the pool release functionality that will remove data from the database.However it has been coded in a very safe way. 
 
**For Escalation/TAC teams:**
This will help to collect logs faster.There is no need to search for commands or spend time in collecting tables and then logs.Everything will be done at the press of a single button.




#**Usage Example:**


This tool needs to be downloaded onto Catalyst Center.  
Make sure you run the tool from /home/maglev only


$ ./cc-assist 



*****************************************************************************
*****************************************************************************
*****                                                                   *****
*****                            CC-Assist                              *****
*****                         Version 1.1.0                            *****
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
 Cisco DNA Center Analyzer Tool logs will be available in a folder named cc-logs.This folder will be created in the same path where the program lies currently.So if you followed the earlier instructions on running the tool from /home/maglev, cc-logs will be available in /home/maglev/ .Depending on the option you choose a sub-folder will be created under cc-logs and the actual logs and tables will be in available as a tar.gz file inside this sub-folder. 

 E.g This is how lan automation log collection folder will look.You need to upload lan_automation_06-24-2024_08-36-21_UTC.tar.gz file to the SR/BEMS
 cc-logs/lan_automation/lan_automation_06-24-2024_08-36-21_UTC.tar.gz
 
 ## How to submit feedbacks or bugs:
 Please raise an issue in github to report any bugs or submit any new feature asks.Please make sure any feature ask you submit would help to troubleshoot catalyst center more efficiently.In case you feel strongly about the feature ask please submit your code as well.That will increase the chances of that feature getting integrated in cc-assist.
