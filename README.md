# RPA-Developer-with-Uipath-Nanodegree_Invoice-Scraping
A process that will scrape relevant data from the invoices for further processing.The Robot will read through emails and download the invoices received in the form of an email attachment as a PDF. It will extract specific data and store those values in an Excel spreadsheet and a subset of values will be uploaded to the Orchestrator Queue. And finally, the robot will email the spreadsheet to yourself when finished.

Project Steps:
-Program a Robot that will “Read the last unread emails” from your mail.
-Program a Robot that will download all the attachments with a naming convention of CustomerName_InvoiceDate_InvoiceNumber.pdf file from the mail with the subject line Techno Computers.
-Program a Robot to save the attachment files in the data folder which has already been created or create it in the Project directory.
-Program a Robot that will “extract the relevant fields from the document”:
 InvoiceNo
 InvoiceDate
 Order Information
 ItemNo
 Description
 Quantity
 Price
 SubTotal
 GST
 Total
-Program a Robot to save the all Order Information details into an excel sheet and save the excel sheet as “CustomerName_InvoiceNumber.xlsx”
-Program the bot to upload the following Order Information details to the Orchestrator Queue:
 SubTotal
 GST
 Total
-Program the bot to email the excel file as an attachment to yourself with the subject line as “Course 2 Automation: CustomerName_InvoiceNumber details uploaded to queue”.
-Repeat Step 4-7 for the remaining invoices.
-Program the robot to successfully end if all the attachments downloaded from the mail in Step 2 are processed.
