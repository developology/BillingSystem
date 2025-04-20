# 🧾 Billing System (GST Calculator)

This is a simple web-based Billing System that calculates the final bill amount including GST. Built using **HTML, CSS, and JavaScript**, it allows users to input the price, quantity, and select a GST rate to generate a final bill.

---

## 🔧 Features

- Enter **price** and **quantity**
- Select **GST rate** (18%, 24%, 36%)
- Automatically calculates:
  - Amount before GST
  - GST Amount
  - Final Amount
- Stores values using **LocalStorage**
- Displays results on a separate page
- Clean and responsive design ✨

---

## 🗂️ File Structure
BillingSystem/ │ 

                 ├── index.html # Input page (price, GST %, quantity)

                 ├── bill.js # Logic to calculate bill and store in LocalStorage 
                 
                 ├── finalbill.html # Displays final bill using stored data

## 📦 How It Works

1. **User enters input** on `index.html`
2. On clicking **"Result"**, values are calculated in `bill.js` and stored in `LocalStorage`
3. The user is redirected to `finalbill.html`
4. `finalbill.html` retrieves data from `LocalStorage` and shows:
   - Total Bill
   - GST %
   - GST Amount
   - Final Amount

---

## 🚀 How to Run Locally

1. Clone the repo or download the files  
2. Open `index.html` in your browser  
3. Fill the form and click **Result**  
4. View the generated bill!

---


---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/5837ea78-0c15-467d-80a8-7ba0e9090403)


![image](https://github.com/user-attachments/assets/29039313-36cf-4afc-b05d-2627d1eaa39d)


## Live Link: https://developology.github.io/BillingSystem/
