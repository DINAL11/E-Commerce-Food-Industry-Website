# 🍔 E-Commerce Food Industry Website

This project is a **real-world Node.js-based E-Commerce web application** built for the **Food Industry**.  
It allows users to browse products, manage carts, and complete secure online payments via PayPal integration.

---

## 🚀 Features
- Responsive UI for food ordering and checkout.
- Cart management with item quantity updates and total calculation.
- Secure PayPal payment integration and order verification.
- MySQL database setup for product, order, and payment tracking.
- Express.js backend with dynamic routing and session management.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MySQL (via XAMPP)  
- **Payment Gateway:** PayPal API  

---

## 📦 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/DINAL11/E-Commerce-Food-Industry-Website.git
cd E-Commerce-Food-Industry-Website
```
### 2. Install dependencies
```bash
npm install
```
### 3. Configure environment variables
Create a .env file in the root directory:
```bash
ini
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=food_ecommerce
PAYPAL_CLIENT_ID=your_client_id
PAYPAL_SECRET=your_secret
```
⚠️ Do not upload your .env file to GitHub.
Add .env to your .gitignore file to keep credentials secure.

### 4. Start the project
```bash
npm start
```
Then visit http://localhost:3000 in your browser.

## 📚 Project Structure
```
csharp
├── public/           # Static files (CSS, JS, Images)
├── views/            # Frontend templates (HTML/EJS)
├── routes/           # Express routes
├── config/           # DB & PayPal configurations
├── app.js            # Main server file
└── package.json
```

## 💳 Payment Integration
Configured PayPal sandbox for testing transactions.

Includes payment verification, order status update, and thank-you page.

