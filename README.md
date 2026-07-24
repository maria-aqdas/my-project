# ☕ Smart Cafe POS & Inventory System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</p>

An interactive, menu-driven Point of Sale (POS) and inventory management CLI application built with Python. Developed to master essential Python data structures specifically **Dictionaries**, **2D Lists (Matrices)**, and **Control Flow Logic**.

---

## 🛠️ System Flow

```mermaid
graph TD
    A[☕ Cafe Menu - Dictionary] -->|Select Items| B[📦 Inventory - 2D Matrix]
    B --> C{User Operations}
    C --> D[1. View Cart & Stock]
    C --> E[2. Add Products]
    C --> F[3. Remove Products]
    C --> G[4. Calculate Total Bill]
    C --> H[5. Sort Alphabetically]
