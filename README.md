# 💸 Travel Payment Splitter (Flutter / Dart)

## 📌 Project Overview

This project started with a simple goal: **make travel expense sharing easy and fair**.

At the beginning, I wanted to become a *mobile app developer*. However, along the way, I realized something honest and important — **UI/UX design is not my strongest talent** 😅. Instead of giving up, I leaned into what I *am* good at.

I was an **accountant**, so I’m very comfortable with **numbers, calculations, and logic**. This app was built for my **community and close friends** to:

* Record who paid what during a trip
* Split all expenses **equally and transparently**
* Reduce awkward conversations like *“Wait… who owes whom?”*

The result is a **functional, calculation-focused Flutter app** that prioritizes correctness over visual polish.

---

## 🎯 Purpose & Philosophy

* This is **not a production-ready app**
* This is a **learning & community project**
* The focus is on:

  * Data modeling
  * Expense calculation logic
  * State flow between pages

Design comes second. **Correct math comes first.**

---

## 🛠 Tech Stack

* **Framework:** Flutter
* **Language:** Dart
* **Paradigm Highlights:**

  * Functional-style operations
  * Chained calculations
  * Clear separation of responsibilities per page

One thing I really enjoyed is how **Dart supports functional programming concepts** while still being very readable. Chaining calculations feels natural and expressive.

---

## 🧭 App Flow

1. **Name Page**

   * Register participants in the trip

2. **Payment Page**

   * Input payments made by each participant
   * Multiple payments supported

3. **Settlement Page**

   * Automatically calculates:

     * Total expense
     * Per-person share
     * Who should pay whom, and how much

Each page is responsible for **one clear role**, keeping the logic easy to trace and debug.

---

## 📂 Project Structure (Simplified)

```
lib/
├── main.dart
├── name_page.dart
├── name_modal.dart
├── payment_page.dart
├── settle_page.dart
```

* `main.dart` – App entry point
* `name_page.dart` – Participant input
* `payment_page.dart` – Expense input
* `settle_page.dart` – Core settlement logic

---

## 🐞 Known Issues & Limitations

* Some **edge cases still cause bugs**
* UI is minimal and not fully polished
* No persistent storage yet

That said:

> **The app is usable** and produces correct results in most real travel scenarios.

---

## 🚀 Future Plans

Someday, I would like to:

* Fix remaining bugs
* Improve validation and edge cases
* Add local storage
* Light UI refinement (without over-designing)

There’s no rush. This project represents **steady growth**, not perfection.

---

## 🙌 Final Notes

This app reflects who I am:

* Not a designer — but a **logical problem solver**
* Not flashy — but **reliable and accurate**
* Built with care for **real people and real use cases**

If you’re reading this as a developer: thank you.
If you’re using this with friends: enjoy your trip ✈️

— *Built with numbers, logic, and sincerity*
