# US Federal IT & Software Contract Leads Feed (SAM.gov)

An automated data pipeline that extracts, deduplicates, and normalizes active US Federal IT, Cloud, and Custom Software contract opportunities from **SAM.gov** on a daily basis.

Designed for GovCon capture managers, IT agencies, and B2G business development teams who want clean, actionable solicitations without spending hours manually filtering SAM.gov every morning.

---

## 🎯 Target NAICS Sectors
* **541511** — Custom Computer Programming Services
* **541512** — Computer Systems Design Services
* **518210** — Data Processing, Hosting, and Related Services
* Adjacent federal IT, cybersecurity, and cloud modernization codes

---

## 📊 Data Schema & Included Fields
Every daily update delivers structured, UTF-8 normalized records containing:
* **Notice ID & Solicitation Title**
* **Department / Sub-tier Agency**
* **NAICS Code & Set-Aside Status** (Small Business, 8(a), WOSB, SDVOSB, etc.)
* **Response Deadline**
* **Point of Contact (POC):** Direct Contracting Officer Name, Email, and Phone Number
* **Direct Links:** Official SAM.gov notice URL and direct solicitation attachment links

---

## 📂 Sample Dataset (Free)
You can inspect the included [`sample_sam_leads.csv`](./sample_sam_leads.csv) file directly in this repository, or download the packaged free sample via Gumroad:

👉 **[Download the Free 15-Lead Sample CSV ($0)](https://rafaelmathias.gumroad.com/l/free-sam-gov-sample)**

---

## 🚀 Daily Live Feed Subscription
Need fresh, active federal IT & software opportunities delivered automatically every day?

👉 **[Get Full Daily Access on Gumroad](https://rafaelmathias.gumroad.com/l/sam-gov-it-leads)**

---

## 🛠️ Tech Stack
* **Data Source:** Official SAM.gov Opportunities API
* **ETL & Automation:** Cloud-scheduled JavaScript / Google Apps Script pipeline
* **Output Formats:** Normalized CSV & Live Cloud Spreadsheet
