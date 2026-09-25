<h1 align="center">🏎️ Car Management & Race Simulation System</h1>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-dsa--oop-concepts">DSA & OOP Concepts</a> •
  <a href="#-installation--usage">Installation & Usage</a> •
  <a href="#-how-it-works">How It Works</a> •
  <a href="#-complexity">Complexity</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LANGUAGE-C%2B%2B11-00599C?style=flat&logo=cplusplus" alt="C++11" />
  <img src="https://img.shields.io/badge/DATA%20STRUCTURES-LINKED%20LIST%20%7C%20QUEUE-007EC6?style=flat" alt="Data Structures" />
  <img src="https://img.shields.io/badge/PARADIGM-OOP-FE7D37?style=flat" alt="OOP" />
  <img src="https://img.shields.io/badge/STATUS-COMPLETED-4C1?style=flat" alt="Status" />
</p>

<p align="center">
  A C++ console-based Car Management and Race Simulation System built to demonstrate practical implementations of Data Structures, Algorithms, Dynamic Memory Allocation, and Object-Oriented Programming (OOP).
</p>

---

## ✨ Features

* **🏎️ Add Cars:** Add individual cars with name, speed, and price parameters.
* **🚗 Add Multiple Cars:** Quickly populate the garage with multiple vehicles.
* **🎲 Random Car Generator:** Automatically generate cars with randomized specifications.
* **📋 Display Garage:** View all cars currently stored in the garage dynamically.
* **🔍 Search Cars:** Query and find cars instantly using their model name.
* **📊 Sort by Speed:** Reorder the garage by top speed.
* **🏁 Race Queue:** Manage race participants using a FIFO queue structure.
* **⚡ Upgrade Cars:** Dynamically upgrade a car's top speed.
* **🗑️ Delete Cars:** Remove unsold or unwanted cars from the garage.
* **🏆 Race Simulation:** Run head-to-head simulations and declare winners based on speed.
* **💰 Sell Cars & 💵 Balance:** Sell vehicles to update the player's wallet balance.

---

## 🧠 DSA & OOP Concepts

This project focuses on implementing fundamental DSA concepts without relying exclusively on built-in standard containers.

| Concept | Usage |
| :--- | :--- |
| **Singly Linked List** | Stores and manages cars dynamically in the garage. |
| **Queue (`std::queue`)** | Maintains race participants adhering to First-In-First-Out (FIFO). |
| **Bubble Sort** | Reorders linked list nodes based on top speed. |
| **Linear Search** | Locates specific cars by model/name. |
| **Dynamic Memory Allocation** | Instantiates and frees car nodes at runtime. |
| **Classes & Objects** | Encapsulates car properties and garage operations. |
| **Pointers** | Handles manual node link management across the list. |

---

## 🎮 Application Menu

```text
------ Car Game Menu ------
1.  Add Car to Garage
2.  Add Multiple Cars to Garage
3.  Generate Random Car
4.  Display All Cars
5.  Search Car by Name
6.  Sort Cars by Speed
7.  Add All Cars to Race Queue
8.  Exit Car from Race Queue
9.  Upgrade Car (Increase Speed)
10. Delete Car by Name
11. Start Race
12. Sell Car for Money
13. Show Balance
14. Exit
