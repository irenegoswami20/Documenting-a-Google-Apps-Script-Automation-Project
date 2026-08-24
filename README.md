# End-to-End Salary Slip Automation Using Google Apps Script

## Project Overview

This project focuses on automating the complete **salary slip generation and email distribution process** using **Google Sheets, Google Apps Script, Google Drive, and Gmail**.

What started as a repetitive manual process was transformed into a two-step automated workflow that generates employee-specific salary slips, stores them as PDFs, and distributes them through email with the correct attachments.

## Step 1 — Automated Salary Slip Generation

Employee salary information is maintained in **Google Sheets**. Using Google Apps Script, the workflow:

* Reads employee-wise salary information
* Generates an individual salary slip for each employee
* Creates a PDF containing employee-specific salary details
* Includes earnings, deductions, CTC and net salary
* Saves each PDF automatically in a dedicated **Salary Slips** folder in Google Drive
* Records the corresponding PDF file path in Google Sheets
* Updates the processing status as **PDF Created / Failed**

<img src="https://github.com/irenegoswami20/Documenting-a-Google-Apps-Script-Automation-Project/blob/7775145cd6387ebf38bd396f284b648a4eafa7d7/employee%20salary%20details.jpg" alt="Image Description" width="600">  
<br>
<img src="https://github.com/irenegoswami20/Documenting-a-Google-Apps-Script-Automation-Project/blob/7775145cd6387ebf38bd396f284b648a4eafa7d7/google%20apps%20script%20code.png" alt="Image Description" width="600">  
<br>
 <img src="https://github.com/irenegoswami20/Documenting-a-Google-Apps-Script-Automation-Project/blob/7775145cd6387ebf38bd396f284b648a4eafa7d7/generate%20salary%20slips%20automation.png" alt="Image Description" width="600">  
<br>
<img src="https://github.com/irenegoswami20/Documenting-a-Google-Apps-Script-Automation-Project/blob/7775145cd6387ebf38bd396f284b648a4eafa7d7/salary%20slips%20created%20-%20drive.png" alt="Image Description" width="600">  
<br>
## Step 2 — Automated Email Distribution

The automation was then extended to create a separate **Email Salary Slips** tab.

The workflow:

* Automatically populates employee names and email IDs
* Links each employee with their corresponding salary slip PDF
* Provides a checkbox-based selection system for email distribution
* Retrieves the correct PDF from Google Drive
* Attaches the salary slip automatically to the email
* Generates a personalized email using the employee's name
* Updates the status to **Email Sent**

<img src="https://github.com/irenegoswami20/Documenting-a-Google-Apps-Script-Automation-Project/blob/7775145cd6387ebf38bd396f284b648a4eafa7d7/email%20salary%20slips%20automation.png" alt="Image Description" width="600">  
<br>
<img src="https://github.com/irenegoswami20/Documenting-a-Google-Apps-Script-Automation-Project/blob/7775145cd6387ebf38bd396f284b648a4eafa7d7/emails%20sent%20-%20gmail.png" alt="Image Description" width="600">

## Automation Workflow

```text
Google Sheets
      ↓
Google Apps Script
      ↓
Salary Slip Generation
      ↓
PDF Creation
      ↓
Google Drive
      ↓
Email Distribution
      ↓
Gmail
      ↓
Employee
```

## Key Outcome

The complete automation was successfully executed **twice**, generating the salary slips and subsequently distributing them through Gmail with the correct PDF attachments.

This eliminated several repetitive manual steps involved in:

* Creating individual salary slips
* Saving PDF files
* Managing file locations
* Selecting attachments
* Drafting repetitive emails
* Sending salary slips individually
* Tracking processing status

## Key Learnings

This project helped me understand that **automation is not just about writing code**. It is about connecting multiple tools and designing an end-to-end workflow that improves efficiency, consistency and reduces repetitive manual effort.

I used **ChatGPT** to assist with developing and refining the Google Apps Script, while the testing, troubleshooting, implementation and execution of the complete workflow were carried out through Google Apps Script.

## Tools & Technologies

* Google Sheets
* Google Apps Script
* Google Drive
* Gmail
* JavaScript
* ChatGPT

## Project Takeaway

This was a valuable hands-on project in combining:

**Data Handling + Scripting + Document Automation + File Management + Email Automation**

into one practical business workflow.

It demonstrated how everyday administrative processes can be transformed into scalable and repeatable automated solutions using tools that are already available within the Google ecosystem.

---

### Topics

`Google Apps Script` `Google Sheets` `Google Drive` `Gmail Automation` `Process Automation` `Document Automation` `Data Analytics` `JavaScript` `Workflow Automation` `ChatGPT` `Learning By Doing`

