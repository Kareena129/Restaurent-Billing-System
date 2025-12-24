# 🍽️ Restaurant Billing System

#### This repository contains the source code for a Restaurant Billing System, a web-based application designed to automate invoice generation, billing calculations, and tax handling for restaurants. The system provides a simple, user-friendly interface for generating detailed invoices with discounts and GST.

## 🚀 Demo
#### Local Demo: http://127.0.0.1:5500/index.html

(Hosted demo can be added later)

# ✨ Features
Billing & Invoice
 - Generate customer invoices dynamically
 - Add multiple food items with quantity and price
 - Automatic total calculation
 - Discount application
 - CGST & SGST calculation
 - Grand total generation

Invoice Management

- View all generated invoices
- Search invoices by customer name
- Date-wise invoice generation
- Clean, printable invoice format

User Experience

- Simple and intuitive UI
- Responsive layout
- Fast calculations with JavaScript
- Real-time invoice preview

# 📸 Screenshots
## Generate Invoice
<img width="1581" height="916" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/41adfee3-b5c1-41d5-9924-a6c23b8162ca" />


## Invoice Preview
<img width="1563" height="934" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/e0292e98-5176-43aa-a501-d989ed7a3627" />


## 🛠️ Tech Stack

- HTML5 – Structure

- CSS3 – Styling & layout

- JavaScript (Vanilla JS) – Logic & calculations

## 📂 Project Structure
     Restaurant-Billing-System/
      │
      ├── index.html
      ├── style.css
      ├── script.js
      ├── screenshots/
      │   ├── invoice-form.png
      │   └── invoice-preview.png
      └── README.md

## ⚙️ Run Locally
Clone the repository
git clone

     https://github.com/YOUR_USERNAME/restaurant-billing-system.git

## Open the project
      cd restaurant-billing-system

## Run

Open index.html in your browser
         OR
Use Live Server in VS Code

## 📊 Billing Logic

- Total = Σ (Quantity × Price)

- Discount = 10% of Total
- Net Total = Total − Discount
- CGST = 9% of Net Total
- SGST = 9% of Net Total
- Grand Total = Net Total + CGST + SGST

## 🔮 Future Enhancements

- Invoice download as PDF
- Database storage (MongoDB / MySQL)
- User authentication
- Admin dashboard
- Payment integration
- Backend support (Node.js / Express)

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository, raise issues, or submit pull requests.

## 📬 Feedback

If you have suggestions or feedback, feel free to reach out or open an issue.

  ⭐ If you like this project, don’t forget to star the repository!
