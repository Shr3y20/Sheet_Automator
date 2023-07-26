## Sheet_Automator
#Description
This project helps an organization to keep track of the enquiries received. The functionality of the sheet after the script is imported is as follows:
1. Removes skipped lines if any in the sheet
2. Fills the due dates automatically (fills the same date as date of received enquiry) in case it is unfilled
3. It sorts the orders date wise and for the same date it sorts the orders in descending order of their quantities
4. If the order is marked close it will shift the order into the closed orders sheet
5. If the quote for the enquiry is not provided, the script will copy paste that row into a sheet called "Currently Pending".
6. It will highlight the enquiry on their due date of follow ups
7. It also highlight priority marked orders with a diffrent color for easier recognition

#Steps
1. On your Google sheet go to Extensions->Apps Script
2. Create a project and copy paste the code
3. Create a new sheet called "Completed Orders"
4. Set the column names:
   a.
   b.
   c.



TLDR: Automated highlighting, sorting, segmentation of quotations received in Google Sheets using Google Apps Script
