# ☕ Smart Cafe POS & Inventory System

<p center>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</p>

An interactive, menu-driven Point of Sale (POS) and inventory management CLI application built with Python. Developed to master essential Python data structures—specifically **Dictionaries**, **2D Lists (Matrices)**, and **Control Flow Logic**.

---

## 🛠️ System Architecture

```text
               ┌─────────────────────────────────────────┐
               │         CAFE MENU (Dictionary)          │
               │  Fixed Products & Unit Price Mapping    │
               └────────────────────┬────────────────────┘
                                    │
                                    ▼
               ┌─────────────────────────────────────────┐
               │         INVENTORY (2D Matrix)           │
               │   [ [Name, Price, Quantity], ... ]      │
               └────────────────────┬────────────────────┘
                                    │
  ┌───────────────────┬─────────────┴───────┬───────────────────┐
  ▼                   ▼                     ▼                   ▼
[1] View Cart    [2] Add Product    [3] Remove Item     [4] Bill Calculation
