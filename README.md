# ⚽ DLS Lineup Optimization (4-3-3)  
Optimize your Dream League Soccer lineup using Linear Programming.

This project automatically selects:
- **Best 11 starting players**
- **Best 9 substitutes (1 GK, 2 DEF, 3 MID, 3 ATT)**  
while **maximizing total performance score (Point)** based on your DLS player dataset.

---

## 📌 Overview

This project uses **Linear Programming (LP)** to solve a real optimization problem:
> *"Among all available players, pick the best possible 20-man squad following formation, position, and substitute constraints."*

Algorithm used:
- **PuLP (Integer Linear Programming)**
- **Binary decision variables (0 = not selected, 1 = selected)**
- **Maximize total Point**

---

## 📊 Dataset

Your dataset includes:
- Player attributes: Speed (SPE), Accuracy (ACC), Stamina (STA), Strength (STR), Passing (PAS), Shooting (SHO), Tackling (TAC)
- Player total score + final point
- Player rank (A/B/C/S)
- Player primary position (GK, CB, RB, LB, CM, DM, AM, LW, RW, CF,…)

You uploaded:
- `Demo_DLS.xlsx` → player stats  
- `Best_Line_up.ipynb` → optimization notebook

---

## 🧠 Optimization Logic

### 🎯 **Goal**
Maximize:
