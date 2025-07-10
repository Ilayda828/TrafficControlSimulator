🚦 Traffic Control Simulator
A JavaFX-based traffic simulation game developed as a course project for CSE1242 Computer Programming II (Spring 2024).
Players manage traffic at urban intersections by controlling traffic lights. The game features level file parsing, car animation logic, 
win/lose mechanics, and a bonus level designer mode.


🎯 Project Objectives
Simulate traffic flow on a grid-based city map

Control traffic lights to reduce congestion and prevent crashes

Read level data from structured .txt files

Use JavaFX PathTransition to animate car movement

Handle collisions, traffic light control, and goal tracking

Bonus: Provide an interactive drag-and-drop level editor


🛠️ Technologies Used
Feature	Technology
Language	Java
GUI Library	JavaFX
Animation & Logic	AnimationTimer, PathTransition
Input Handling	File I/O, Custom Parsers
Game Design	OOP, MVC Pattern

🧩 Game Elements
RoadTile: Straight, curved, T-, and cross-shaped roads with rotation support

Building: Start/end points for cars (e.g., homes, offices)

TrafficLight: Clickable red/green lights that affect car decisions

Car: Moves through the map, responds to lights, detects crashes

Level Parser: Parses metadata, map layout, roads, buildings, lights, and paths

Designer Mode: Build and export levels with a user-friendly GUI

🎮 Gameplay
Cars spawn randomly and follow predefined routes

Players change traffic lights to manage flow

Too many crashes leads to a game over

Reaching the goal advances to the next level

UI shows live stats (number of crashes and cars that reached destination)

🏁 Win/Lose Conditions
✅ Win: Deliver the required number of cars safely to their destination

❌ Lose: Exceed the allowed number of crashes
