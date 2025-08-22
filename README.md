# 🔎 Open Source Red Flag Checker

An open-source web app to check whether a phone number, bank account, or Twitter handle has been reported as **spam, fraud, or scam**.  
This project combines public / open sources (e.g., [cekrekening.id](https://cekrekening.id), [aduankonten.id](https://aduankonten.id)) into a single elegant UI.  

## ✨ Features
- Check **phone numbers, bank accounts, or Twitter handles**
- Pulls reports from open-source JSON data
- Displays **tags, last report date, and sources**
- Futuristic UI (cinematic gradient design)
- Works fully client-side (static HTML) → perfect for **GitHub Pages**

## 📂 Project Structure
/data
├── reports-phone.json
├── reports-bank.json
└── reports-twitter.json
index.html
README.md
LICENSE

## 🚀 Deployment
1. Fork or clone this repository  
2. Edit the `RAW_BASE` in `index.html` with your GitHub username & repo name:
   ```js
   const RAW_BASE = 'https://raw.githubusercontent.com/<username>/<repo>/main/data';
Commit and push changes

Enable GitHub Pages → Settings > Pages > Source: main branch, /root

Your checker is live at https://<username>.github.io/<repo>/

📊 Example Test Data
Phone: +6281234567890 (spam loan, source: Kominfo Aduan Konten)

Bank Account: 1234567890 (fraud case, source: cekrekening.id)

Twitter: @fake_investasi (investment scam, source: Aduan Konten)

📜 License
This project is licensed under the MIT License — you are free to use, modify, and share with attribution.
