# Desktop-Notifier

A Python Script to Create Desktop Notification of Various Linux Commands.

The script fetches the Linux Command and it's link from the Excel file and then pushes a desktop notification with the Title and the Link and using the link, you can learn about the Linux Command. 

The Script delets the row once the notification is sent and then saves the workbook after deleting the row. 

![Screenshot from 2021-01-16 21-32-23](https://user-images.githubusercontent.com/74530357/104816825-8e657900-5843-11eb-81a5-d7cf899efc06.png)

![Screenshot from 2021-01-16 21-33-20](https://user-images.githubusercontent.com/74530357/104816840-accb7480-5843-11eb-8566-34e9b2dbeaa5.png)

TIP: You can add this to the cron tab and then make the python script push a notification at a regular interval to remind you learn the commands. 

Concepts used:
    Desktop Notifications with notify2 module
    Spreadsheet handling with openpyxl module
    crontabs [If you want to schedule the scripts at a regular interval]
