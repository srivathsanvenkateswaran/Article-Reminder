# Article-Reminder

A Python Script to Create Desktop Notification of Articles which are listed inside the spreadsheet.

The script fetches the Article and it's link from the Excel file and then pushes a desktop notification with the Title and the Link and using the link, you read the particular Article. 

The Script also deletes the row once the notification is sent and then saves the workbook after deleting the row to ensure that the same link doesn't appear twice. 

# Use-Case

You can add all the articles which you would like to read later into the spreadsheet and this script will pop up the notification with the Title and Link of the Article and you can directly read it by clicking on the notification. 

After configuring the spreadsheet, schedule the python script either with crontabs [For Linux/MacOS] or using Task Scheduler [For Windows]. 

You are free to be creative and tinker with the code to help you remind various other tasks with the help of Desktop Notifications. 

# Screenshots

![Screenshot from 2021-01-16 21-32-23](https://user-images.githubusercontent.com/74530357/104816825-8e657900-5843-11eb-81a5-d7cf899efc06.png)

![Screenshot from 2021-01-16 21-33-20](https://user-images.githubusercontent.com/74530357/104816840-accb7480-5843-11eb-8566-34e9b2dbeaa5.png)

TIP: You can add this to the cron tab and then make the python script push a notification at a regular interval to remind you learn the commands. 

# Concepts used
    
    Desktop Notifications with notify2 module
    Spreadsheet handling with openpyxl module
    crontabs [If you want to schedule the scripts at a regular interval] for Linux and MacOS
    Task Scheduler [If you want to schedule the scripts at a regular interval] for Windows
    
NOTE: I would highly appreciate having the Article Title and It's link in a separate Spreadsheet/Txt file as a back-up or for future reference because the script will delete the Title and the Link once it pushes the notification. 
