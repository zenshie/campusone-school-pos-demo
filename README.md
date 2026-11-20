# CampusOne School POS Demo

A responsive front-end demonstration that combines:
- Tuition and fee collection with student account balances and payment history
- Canteen POS
- Bookstore POS
- Student directory
- Shared inventory management
- Transaction records and CSV export
- Revenue and inventory reports

## Run
Extract the ZIP and open `index.html` in a modern browser.

## Deploy with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `script.js`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site. Open the URL displayed in the Pages settings.

## Demo behavior
- Select a student in Tuition & Fees, then record a payment. The student's balance and payment history update.
- In Canteen POS or Bookstore POS, add products and complete a sale. The relevant inventory quantity decreases.
- Add, edit, and delete products from Inventory.
- Add sample students from the Student Directory.
- Transactions and CSV export update as demo records are created.
- Data is saved using browser localStorage on the current browser/device.

## Important limitations
This is a browser-only prototype with fictional sample records. It is not production-ready school financial software. It has no login/authentication, roles or permissions, server, shared database, cloud backup, multi-device synchronization, accounting integration, payment gateway, barcode scanner, receipt printer, official BIR-compliant receipt issuance, or audit-grade logs. Browser storage can be cleared and is not suitable as the school's sole record. Do not enter real student personal information or use it for actual fee collection. Any live deployment requires secure backend storage, privacy controls, access permissions, backups, and review of applicable Philippine data-protection, accounting, and tax requirements.
