This README file is structured to help you document your KBFC away jersey ordering site. You can save this content in a file named README.md in your project folder.

KBFC Away Jersey Order Portal
This project is a simple, lightweight web portal designed for fans to order the new Kerala Blasters FC (KBFC) away jersey. Order details are captured directly into a Google Sheet for easy management and fulfillment.

🚀 Features
Simplified Ordering: A user-friendly interface to input customer details and size preferences.

Google Sheets Integration: All orders are automatically synced to a centralized Google Sheet, eliminating the need for a complex backend database.

Responsive Design: Works seamlessly on both mobile and desktop devices.

🛠 How It Works
The system uses an HTML/JavaScript frontend to capture order data. This data is sent to a Google Form (or a Web App script) that feeds directly into your designated Google Sheet.

Setup Instructions
Google Sheet Preparation:

Create a new Google Sheet.

Add headers for your required fields: Timestamp, Name, Phone Number, Size, Quantity, and Address.

Connecting the Sheet:

Easiest Method: Create a Google Form that corresponds to your sheet headers. Embed the Google Form link into your website's "Order Now" button or iframe.

Advanced Method: Use a tool like SpreadSimple or a custom Google Apps Script to link your HTML form directly to your spreadsheet without the Google Form interface.

Deployment:

Host your static files (HTML, CSS, JS) on a free service like GitHub Pages, Vercel, or Netlify.
