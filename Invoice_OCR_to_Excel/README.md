# 📄 Invoice Report Bot – UiPath Automation

This project is a UiPath automation developed by **Matt Solutions**. It automatically generates an invoice report in Excel and sends it via email. The bot can be shared across environments and configured to dynamically select the recipient.

---

## 🛠 Features

- Extracts invoice data and compiles it into a structured Excel report  
- Names the report file dynamically using today’s date  
- Sends the report via email using Outlook  
- Allows user input to set the recipient (e.g., financial controller)  
- Can be configured to run manually or scheduled via UiPath Orchestrator  

---

## 📁 Project Structure

```
InvoiceReportBot/
├── Main.xaml            # Main workflow
├── Project.json         # Project metadata and dependencies
├── ReadMe.md            # This documentation
├── Invoices/            # Folder where reports are saved
└── .gitignore           # Hides sensitive or unnecessary files
```

---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/InvoiceReportBot.git
   ```
2. Open the project in **UiPath Studio**.  
3. Make sure your system has Outlook configured for sending emails.  
4. If required, update the default email recipient stored in the environment file or via user input.  
5. Run the workflow manually or deploy it via Orchestrator.

---

## 🧠 Notes

- This bot uses the **Use Excel File** and **Use Outlook Account** activities – ensure you have the necessary packages installed in UiPath.
