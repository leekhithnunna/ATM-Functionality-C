# ATM-Functionality-C
A C program that simulates the basic functioning of an ATM machine with multi-language support (English and Hindi).

# Functioning of ATM (English and Hindi) in C

This project is a simulation of an ATM machine built using the C programming language. It features a simple console-based interface, supporting **multi-language interactions (English and Hindi)**, basic banking operations like balance inquiry, withdrawal with denomination breakdown (using ASCII art), quick cash, and mini-statements.

The program is designed to demonstrate the foundational concepts of **C programming**, **control structures**, **functions**, **arrays**, and **terminal-based UI** using ANSI escape codes.

---

## 🌐 Run the Project on [OnlineGDB](https://www.onlinegdb.com/)

As this project uses the `ncurses` library (Linux-specific), it is **recommended to run on OnlineGDB** or a similar online compiler for demonstration purposes.

### Steps:
1. Open [OnlineGDB](https://www.onlinegdb.com/online_c_compiler).
2. Copy and paste the code into the editor.
3. Click **Run** to execute the program.

---

## ✨ Features

- **Language Selection**: Choose between English and Hindi for interaction.
- **Account Login**: Validate users by account number and PIN.
- **Banking Operations**:
  - **Balance Inquiry**
  - **Withdrawal with Denomination Breakdown (ASCII art of currency notes)**
  - **Quick Cash & Fast Cash Options**
  - **Mini-Statement Generation**
  - **Account Transfer Simulation**
  - **Service Assistance**
- **Animated ATM Welcome Screen**: Colorful terminal effects using `ncurses` and ANSI escape codes.

---

## 🏦 Supported Functionalities

| Option          | Description                                           |
|-----------------|-------------------------------------------------------|
| 1️⃣ Withdrawal   | Withdraw cash from your account with denomination breakdown. |
| 2️⃣ Bank Statement | Get a mini-statement with mock transaction history.   |
| 3️⃣ Balance Inquiry | Check your current account balance.                   |
| 4️⃣ Quick Cash   | Withdraw a preset amount (₹15,000).                     |
| 5️⃣ Fast Cash    | Choose preset amounts like ₹100, ₹500, ₹2,000, etc.     |
| 6️⃣ Service      | Contact your bank branch for services.                  |
| 7️⃣ Account Transfer | Simulate transferring funds between accounts.        |

---

## 🔧 Technologies Used

- **C Programming Language**
- **NCURSES Library** for terminal graphics (`initscr()`, `attron()`, etc.)
- **ANSI Escape Codes** for colorful text output
- **OnlineGDB** for online compilation and execution

---

## 🚀 Sample Screens

< Add screenshots of your ATM welcome screen, withdrawal, and language selection screens here if possible >

---

## 📑 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

- **Leekhith Nunna**
---

## 💡 Notes

- This project is a **simulation** and does not interact with real banking systems.
- The ATM logic is based on **static data** (hardcoded account numbers, PINs, and balances).
- Feel free to explore and extend the functionality!
