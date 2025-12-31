# 🎯 Mega da Virada Lottery Checker (C# Console App)

A robust **C# Console Application** designed to validate lottery bets against the official *Mega da Virada* draw results.  
This project demonstrates **clean code practices**, **file handling**, **data validation**, and **user-friendly console output**, making it a strong addition to a professional portfolio.

---

## 🚀 Project Overview

This application reads lottery bets from a CSV file, compares them with the drawn numbers entered by the user, and determines whether any bet achieved:

- **Sena (6 hits)**
- **Quina (5 hits)**
- **Quadra (4 hits)**

The results are displayed in the console with **colored output** and also exported to a text file for record keeping.

---

## ✨ Key Features

- Console-based interaction
- Input validation (numbers between 1 and 60, no duplicates)
- Supports bets with **6 or more numbers**
- Automatic detection of:
  - 🏆 Sena
  - 🥈 Quina
  - 🥉 Quadra
- Colored console output:
  - Green for winning scenarios
  - Red for no wins
- File-based input and output
- UTF-8 support (emojis and special characters)
- Clean, readable, and maintainable code

---

## 📂 File Structure

```text
C:\
 └── apostas.csv

Downloads\
 └── resultado_mega.txt
