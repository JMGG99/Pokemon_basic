# Pokémon Battle Game

## Description
This is a simple Pokémon battle game implemented in Python using Object-Oriented Programming (OOP). The game allows two Pokémon to battle, using either normal attacks or special moves. Each Pokémon has its own stats, including attack, defense, speed, life points, and stamina.

## Features
- Three Pokémon: **Squirtle, Charmander, and Bulbasaur**.
- Type-based strengths and weaknesses that affect damage calculation.
- Two types of attacks: **Normal Attack** and **Special Move**.
- Turn-based battle system where Pokémon take turns attacking based on their speed.
- Healing system using **Pokémon Center** to restore life points and stamina.

## How to Play
1. Two Pokémon are selected for battle.
2. The Pokémon with the highest speed attacks first.
3. Each turn, players choose between a **Normal Attack (1)** or a **Special Move (2)**.
4. Special Moves consume stamina and deal extra damage if enough stamina is available.
5. The battle continues until one Pokémon's life points reach zero.
6. The winning Pokémon is announced.

## Classes and Methods
### **Pokemon Class**
Represents a generic Pokémon with:
- Attributes: `name`, `type`, `strengths`, `weaknesses`, `atk`, `defense`, `speed`, `life_points`, `stamina`.
- Method `attack(rival_pokemon, movement)`: Handles attacks, taking into account strengths, weaknesses, and stamina.
- Method `Pokemon_center()`: Restores life points and stamina.

### **Derived Pokémon Classes**
- **Squirtle** (Water type, strong against Fire, weak against Plant)
- **Charmander** (Fire type, strong against Plant, weak against Water)
- **Bulbasaur** (Plant type, strong against Water, weak against Fire)

### **Fight Function**
- Controls the battle sequence.
- Determines attack order based on speed.
- Alternates turns between the two Pokémon until one faints.

## Requirements
- Python 3.x

## How to Run
1. Save the script as `pokemon_battle.py`.
2. Run the script in a Python environment:
   ```bash
   python pokemon_battle.py
   ```
3. Follow the on-screen prompts to play the game.

## Future Improvements
- Add more Pokémon with unique abilities.
- Implement multiplayer mode.
- Enhance AI for non-human-controlled Pokémon.
- Introduce graphical user interface (GUI).

## Author
Developed by Julio Gulfo.

