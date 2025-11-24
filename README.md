# 2048 Turtle Game (Python)

A simple and visually appealing implementation of the classic **2048 game** using the built-in Python `turtle` graphics module.
This project recreates the game mechanics of tile merging, random tile generation, keyboard controls, and a color-coded grid.

---

## 📌 Project Motivation

The purpose of this project is to:

* Understand how graphical programs work using Python’s `turtle` module
* Explore game logic such as tile merging and grid movement
* Provide a beginner-friendly project to learn event handling, screen updates, and structured coding
* Recreate the classic 2048 puzzle game in a minimalistic yet functional form

This project is perfect for students and beginners building their first GUI game in Python.

---

## 📊 Data / Grid Description

The game uses a **4×4 numeric grid** to represent all game tiles:

```python
grid = [
    [0, 0, 0, 16],
    [0, 0, 8, 0],
    [0, 4, 0, 0],
    [2, 4, 8, 16]
]
```

* `0` means an empty tile
* Any other number (2, 4, 8, …) represents a tile value
* Tiles merge when two equal values collide
* After each move, a random **2** or **4** appears on an empty tile

Color mapping for tiles is stored in a dictionary, allowing customization.

---

## 🕹️ How to Use

### **1. Install Python**

Make sure Python 3.x is installed on your machine.
To check:

```bash
python --version
```

### **2. Save the script**

Save the file as:

```
2048_turtle.py
```

### **3. Run the game**

```bash
python 2048_turtle.py
```

### **4. Controls**

Use your keyboard arrow keys:

* ⬆️ **Up Arrow** – move tiles up
* ⬇️ **Down Arrow** – move tiles down
* ⬅️ **Left Arrow** – (logic not implemented yet)
* ➡️ **Right Arrow** – (logic not implemented yet)

### **5. Game Window**

A Turtle graphics window will open automatically with the 4×4 grid.

---

## 👤 Contact Information

Feel free to contact the developer for improvements or suggestions.

**Developer:** Pranav Dange
**Email:** *(add your email here)*
**GitHub:** *(add your GitHub link here)*

---
