# 🤖 UiPath Robot Automation

This repository contains UiPath automation workflows designed to streamline business processes. Each project is built for reusability, clarity and ease of deployment.

## 📂 Contents

- **Invoice OCR to Excel Bot**  
  Extracts key data from PDF invoices (e.g., Customer, Product, Amounts) using OCR and sends a summary Excel report via email. Recipient email is stored in a `.env` file.
- **Daily Briefing Bot**  
  Sends a daily email summary including weather in Warsaw, currency exchange rates, and top world news headlines. Uses OpenWeatherMap and Google News RSS. Configurable via `.env` file.

## 🛠 How to Use

1. Download chosen project folder  
2. Open the project in **UiPath Studio** and install required packages  
3. If necessary, create a `.env` file in the root directory as in the example:

   ```
   VARIABLE=value
   ```

4. Ensure programs used by the workflow are installed  
5. Run the bot

## 🚀 Running via UiPath Assistant:
After publishing the project from **UiPath Studio** to **Orchestrator** or locally, you can run it directly from **UiPath Assistant**. To do this:
1. Open **UiPath Assistant**.
2. Locate the published project in the Assistant.
3. Click `Run` to execute the automation.

> **Note:** Ensure that your **UiPath Assistant** is properly connected to Orchestrator or has access to the local project.

