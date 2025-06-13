# 🏀 Bouncing Ball using Python

This project simulates a **bouncing ball** using Python’s built-in `turtle` graphics. It demonstrates basic physics like gravity, acceleration, and energy loss upon bouncing, with support for multi-direction movement.

---

## 🚀 Features

- 🎾 **Gravity Simulation**: Acceleration downward due to gravity.
- 📉 **Energy Loss**: Ball velocity reduces on each bounce.
- ↕️ **Bidirectional Movement**: Ball bounces off all walls—bottom, left, right.
- 🎮 **Interactive Animation**: Real-time animation using `turtle`.
- 🔧 **Configurable Parameters**: Set gravity, loss factor, and window dimensions.

---

## 🗂️ Project Structure
Bouncing-Ball-using-Python/
├── bouncing_ball.py # Main Python script using turtle
├── requirements.txt # Project dependencies (if any)
├── README.md # Project documentation
└── LICENSE # MIT License file

## ⚙️ Setup & Run

### 1. 🔄 Clone the Repository
```
git clone https://github.com/AaryaMehta2506/Bouncing-Ball-using-Python.git
cd Bouncing-Ball-using-Python
```
### 2. 🧪 Install Dependencies
No external libraries required—just ensure you have a modern Python version (3.7+).
Optionally, create a virtual environment:
```
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
```
### 3. 🚀 Run the Simulation
```
python bouncing_ball.py
```

A turtle graphics window will open displaying the bouncing ball animation. Press the window’s close button to stop.

## 🧠 How It Works
Initializes turtle.Screen() and turtle.Turtle() for graphics.

Sets up simulation constants like gravity, velocity, and energy loss.

Runs a while True loop to update ball position and velocity.

Reverses velocity upon hitting bottom or walls, applying energy loss for realism.

## 🙋‍♀️ Customization
Feel free to tweak these parameters inside bouncing_ball.py:
gravity = -0.005
energy_loss = 0.95
width = 600
height = 400
Adjust them to experiment with different bounce behaviors!

## 🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository

Create a new branch:
```
git checkout -b feature-name
```
Commit your changes and push to your fork

Open a pull request explaining your improvements

## 📄 License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE).

## 👩‍💻 Author

**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)
