# Dark Chatbot Builder (Full)

This is a feature-rich chatbot builder that allows users to define trigger phrases and assign responses such as text, URLs, documents, email templates, quotes, and CSV-linked data.

## 💡 Features

- ✅ Bootstrap 5 dark theme with colorful accents
- ✅ Add trigger-response pairs with various types
- ✅ WYSIWYG editor for formatted email/quote templates
- ✅ CSV import for contact and vehicle data
- ✅ JSON export/import for full backup and restore
- ✅ Real-time chatbot preview
- ✅ Embedded document and link rendering

## 📂 Structure

- `index.html` — Main interface
- `README.md` — This file

## 🛠 Usage

1. Open `index.html` in your browser.
2. Add a trigger, select a response type, and define content.
3. For CSV responses, import a contact or vehicle CSV.
4. Use WYSIWYG editor for email and quote templates.
5. Export your chatbot setup as JSON or re-import anytime.

## 🗃 CSV Format Example

### Contact CSV:
```
company,name,phone,email,address
Ryder Vehicle Sales,Thomas Overstreet,405-592-4292,thomas_overstreet@ryder.com,15 S. Morgan Rd, Oklahoma City, OK 73128
```

### Quote CSV:
```id,description,amount
1,Vehicle Purchase,15000.00
2,Maintenance Service,500.00
2,P2K Warranty,4500.00
3,PM SelectCare,644.00
4,Safety Services,600.00
5,Admin Fee,200.00
6,Document Fee,25.00
7,Total,add(1,2,3,4,5,6)
```

### Vehicle CSV:
```
id, make,model,year
123456, Freightliner,Cascadia 125, 2020
```

## ☁ Hosting

You can host this app on:
- Netlify
- GitHub Pages
- Hostinger (via public_html folder)

Just drag and drop the `index.html` and any assets to your hosting provider’s static site area.

## 🔒 Notes

- All data is stored locally in the browser (via localStorage).
- You can export and import chatbot configurations via JSON for backup or sharing.

## 📬 Need Help?

You can request custom integrations (e.g., Google Sheets, GPT, Firebase) anytime.

---
Built with ❤️ by ChatGPT