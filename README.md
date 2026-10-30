# SecurePay – Digital Payment App

A full-stack digital payment application built with **HTML, CSS, JavaScript** and **Firebase**.

## Features

- User Authentication (Email/Password)
- Real-time Wallet Balance
- Send Money to other users
- Mobile Recharge
- Electricity Bill Payment
- DTH Recharge
- Credit Card Bill Payment
- Transaction History
- SHA-256 Audit Ledger (Tamper-proof transaction chain)
- QR Code for receiving money
- Profile Management
- Notifications

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript
- Backend: Firebase Authentication + Cloud Firestore
- Security: Firebase Security Rules
- Special Feature: SHA-256 Hash based Audit Ledger

## How to Run

1. Clone / Download the project
2. Open the folder in VS Code
3. Install Live Server extension
4. Right click on `index.html` or `login.html` → Open with Live Server
5. Create an account and start using

## Firebase Setup

- Project ID: `pay-new-fa48d`
- Authentication: Email/Password enabled
- Firestore: Used for users, transactions & audit ledger

## Project Structure

- `login.html` / `register.html` → Authentication
- `dashboard.html` → Main home screen
- `send-money.html` → Transfer money
- `recharge.html`, `electricity.html`, `dth.html`, `credit-card.html` → Bill payments
- `passbook.html` → Transaction history
- `audit-ledger.html` → SHA-256 chain
- `receive.html` → Receive money + QR
- `profile.html` → User profile
- `notifications.html` → Alerts

## Author

Shraddha Tiwari
Yash Tomar
