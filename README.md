# My Puppy Diet Record - AppSheet Project

This repository contains a full backup of the **Puppy Diet Record** application. This app was designed to track daily food intake (Dry Food, Meat, etc.) and medications, featuring automated daily summaries and trend charts.

## 📱 Device Compatibility
This app is cross-platform and can be accessed on:
* **Android:** Via the AppSheet App or Chrome browser.
* **iPhone (iOS):** Via the AppSheet App or Safari (using "Add to Home Screen").
* **Tablets:** Full support for iPad and Android tablets.
* **Computer:** Accessible via any web browser (Chrome, Safari, Edge).

---

## 📂 Backup Files Included

1.  **Application Documentation.pdf**
    * Contains the "Brain" of the app: column structures, view settings, slices, and UX configurations.
2.  **DietSummary-A1 Formula.txt**
    * Contains the specific Google Sheets `QUERY` formula used to calculate the 7-day totals for the "Dry Food" trend chart.
3.  **My Puppy Diet Record.xlsx**
    * The raw data source and worksheet structure.

---

## 🛠️ How to Restore the App
If you need to rebuild the app from this backup:
1.  Upload the `.xlsx` file to your Google Drive.
2.  Open **AppSheet.com** and select **"Create a new app"** using the uploaded spreadsheet as the data source.
3.  Open the **Application Documentation.pdf** to reference and re-input your:
    * **Valid_If** formulas for dependent dropdowns.
    * **Chart settings** for the Diet Trends view.
4.  Copy the formula from the `.txt` file into cell **A1** of your "DietSummary" sheet to restore the automated charts.

---

## 📅 Last Updated
* **Date:** April 2024
* **Status:** Fully functional prototype with 7-day rolling filters.

Final Tip:
When you upload your .xlsx file to GitHub, remember that GitHub acts only as a storage vault. To actually run the app again, you will always need to move that Excel file back into Google Drive first, as AppSheet needs a "live" cloud connection to show the data on your iPhone or Android.
