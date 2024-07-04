# Secure Email Report Processing Automation

This README provides instructions for automating the retrieval of Payroll Items from a secure email attachment, downloading the PDF report, and sending it for easy access by other departments using UiPath platform.
## Instructions

1. **Cleanup the downloads folder:**
    - Delete previously downloaded attachments.

2.  **Identify and Open the Email:**
    - Search emails with the subject **"Payroll Items."**
    - Open the email based on the date (most recent if the script runs daily).

3. **Download or Open the Attachment:**
    - If the attachment is already available, download it directly to the Downloads folder.
    - Alternatively, if the attachment is in secure `.html` format, open it directly.

4. **Access the Secure Portal:**
    - A secure portal login will prompt for credentials.
    
5. **Download the PDF Report:**
    - After logging in and accessing the report, look for the option to download it in PDF format.

6. **Send the Report:**
    - Once downloaded, send the PDF report to **`payroll@xxx.com`**.

