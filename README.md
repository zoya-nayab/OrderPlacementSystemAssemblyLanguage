# 🍔 Order Placement System — Aena's Cafe

A **64-bit x86 Assembly Language** project that simulates a food ordering system for *Aena's Cafe*, built as part of the Computer Organization and Assembly Language course at **Institute of Business Management (IoBM)**.

---

## 👥 Team Members

| Name | Student ID |
|------|-----------|
| Zoya Nayab | 20231-34552 |


**Course Instructor:** Muhammad Irtiza  
**Course:** Computer Organization and Assembly Language — CSC211  
**Semester:** Fall 2024

---

## 📌 Project Overview

This project implements a menu-driven food ordering system in Assembly Language. The customer can enter their name, browse a categorized menu, select items and quantities, and receive a printed receipt with their total bill.

---

## ✨ Features

- **Customer Name Input** — Personalized receipt with the customer's name
- **Menu Categories** — Burgers, Pizzas, Biryanis, Beverages, and Teas
- **Quantity Selection** — Choose how many of each item to order
- **Bill Calculation** — Automatically calculates total price based on selections
- **Repeat Ordering** — Option to add more items before finalizing
- **Receipt Generation** — Displays a clean final receipt with total amount
- **Input Validation** — Handles invalid menu choices with an error message

---

## 🛠️ Tech Stack

- **Language:** x86 Assembly (64-bit)
- **Library:** Irvine32 (for I/O operations — `WriteString`, `ReadInt`, `WriteInt`)
- **IDE:** Visual Studio Code
- **Platform:** Windows

---

## 🚀 How to Run

1. Open the project in **Visual Studio Code**
2. Make sure the **Irvine32** library is set up and linked
3. Assemble and link the `.asm` file using MASM
4. Run the executable in the terminal
5. Follow the on-screen prompts to place your order

---

## 📋 How It Works

1. The program asks for the customer's name
2. A menu is displayed with 5 categories (1–5)
3. The customer picks a category, then selects an item (1 or 2)
4. The customer enters the quantity
5. The price is calculated and added to the running total
6. The customer is asked if they want to add more items (`Y/N`)
7. Once done, a receipt is printed with the total bill and a thank-you message

---

## ⚠️ Limitations

- GST is not currently calculated (planned for future)
- Items cannot be removed or modified once added to the order

---

## 🔮 Future Improvements

- Add GST calculation to display tax-inclusive totals
- Allow item modification or removal before checkout
- Expand the menu with more categories and items
- Save order history for repeat customers

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `ORDER_PLACEMENT_SYSTEM_CODE_FILE_.docx` | Full Assembly source code |
| `ORDER_PLACEMENT_SYSTEM_REPORT_.docx` | Detailed project report |

---

> *"Thank you for visiting Aena's Cafe!"* ☕
