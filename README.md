# powerbi_reporting_automation
This project has been developed to send power bi reports on a daily basis for commercial leaders.

# Description
The project consists of a python script file and a .bat file to schedule the execution of the script.

The Python script automates several tasks:

1. It interacts with a Power BI dashboard to export reports.
2. It downloads the reports in PDF format.
3. It moves the downloaded PDF files to specific directories.
4. It renames the downloaded files based on the current date.
5. It opens WhatsApp Web and sends the reports as attachments to a specific group or contact.

Here's a breakdown of the main functionalities:

- The script uses Selenium to control a web browser (Google Chrome) and interact with the Power BI dashboard.
- It locates specific elements on the webpage using XPath expressions.
- After exporting the reports from Power BI, it waits for the files to be downloaded.
- Once the files are downloaded, it moves them to predefined directories and renames them based on the current date.
- After processing the reports, it uses Selenium to open WhatsApp Web, select a specific contact or group, and send the reports as attachments.

Overall, this script automates the process of exporting reports from Power BI and sharing them via WhatsApp.
