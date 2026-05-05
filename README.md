 # 🐾 Virtual Pet

An interactive command-line Python game where you care for a virtual pet by feeding it, playing with it, and keeping it alive.

## 📌 Features
- Object-oriented design using Python classes
- Real-time state management (happiness & hunger levels)
- Game over conditions with boundary checks
- Menu-driven interface with input validation
- Simulated time passing using `time.sleep()`

## 🛠️ Tech Stack
Python, OOP, time module

## ▶️ How to Run

```bash
python virtual_pet.py
```

Name your pet and choose actions from the menu to keep it happy and fed.

## 🎮 Gameplay
```
Menu:
1. Feed the pet
2. Play with the pet
3. Check pet's status
4. Quit
```

- Hunger ≥ 100 → Game Over (too hungry)
- Happiness ≤ 0 → Game Over (too sad)

## 📁 Project Structure
```
Virtual_pet/
├── pet.py
└── README.md
```

## 🧠 Skills Demonstrated
- Python OOP (classes, constructors, methods)
- State management and boundary validation
- Control flow, loops, and user input handling
