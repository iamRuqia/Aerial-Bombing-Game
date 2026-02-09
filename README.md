# Aerial-Bombing-Game
My first CPP Game
Air Bombardment Game (بمباران هوایی)
A classic terminal-based aerial bombardment game written in C++ using Windows Console API. Control an airplane, drop bombs on buildings, and navigate through a cityscape while avoiding collisions.

🎮 Features
Retro Console Graphics – Uses Windows Console Buffer for smooth rendering
Dynamic Gameplay – Adjustable flight speed, altitude management, and bombing mechanics
Collision Detection – Avoid buildings with your airplane and wingtips
Scoring System – Earn points for successful hits, lose points for misses
Persian Interface – Menu and instructions in Persian (Farsi)
Real-time Feedback – Visual and audio feedback for hits/misses

🛠️ Controls
Spacebar – Drop bomb
Up/Down Arrow – Increase/decrease speed (1-3 levels)
Q – Quit game

📊 Game Mechanics
Altitude decreases over time – maintain height by managing speed
Buildings have random heights (2-6 floors)
Score = (building floors × 10) for hits, -5 for misses
Game ends if you crash into buildings or descend too low

🖥️ Technical Highlights
Object-oriented design with GameObject inheritance
Double-buffered console output for flicker-free animation
Custom rendering system using CHAR_INFO buffer
Real-time keyboard input handling

Perfect for demonstrating console game development, C++ OOP principles, and real-time interactive systems in a lightweight terminal environment.
Why it's cool: This isn't just another Snake game – it's a full aerial combat simulator with physics, collision systems, and retro aesthetics, all in the Windows console! Great example of what you can build with native Windows APIs and clever programming.
