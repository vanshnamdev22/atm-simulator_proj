# 🏧 ATM Simulation (Python CLI)

A simple command-line ATM simulation written in Python. This project mimics basic ATM operations such as checking balance, depositing money, and withdrawing funds.

---

## 📋 Features

- ✅ Check account balance  
- 💰 Deposit funds  
- 💸 Withdraw money  
- ❌ Exit the simulation  
- 🧠 Simple input validation and balance check

---

## 🧰 Requirements

No external libraries are needed. Just run it with Python 3:

```bash
python atm_simulation.py
```

---

## 🚀 How It Works

1. On running the script, the user is presented with a menu of operations:
   - Check balance
   - Deposit amount
   - Withdraw amount
   - Exit

2. The account starts with a default balance of **100,000**.

3. Each transaction updates and displays the current balance.

---

## 🧠 Example Session

```
ATM Simulation machine
Select an operation you want to perform:
1. Check Balance
2. Deposit amount
3. Withdraw amount
4. Exit
Enter option number: 1
The available balance is: 100000

Enter option number: 2
Enter amount you want to deposit: 5000
The deposited amount is 5000. The total new amount is: 105000

Enter option number: 3
Enter amount you want to withdraw: 20000
The withdrawal amount is 20000. The available amount is: 85000
```

---

## 🧱 Project Structure

- `ATM` class:
  - `check_balance()` – returns current balance
  - `deposit(amount)` – adds amount if valid
  - `withdraw(amount)` – deducts if sufficient balance exists

- `main()` function:
  - CLI menu loop with user interaction

---

## 📌 Notes

- This is a basic CLI simulation. No PIN/authentication is implemented.
- Input validation is minimal — ideal for educational purposes.
- Can be extended to include user accounts, file/database storage, or GUI.

---

## 📄 License

This project is free to use for learning and personal projects.

