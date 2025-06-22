# GAME DEVELOPMENT:SNAKE GAME

COMPANY : CODTECH IT SOLUTION

NAME : PRASHANT KUMAR SINGH

INTERN ID : CT04DF551

DOMAIN : C++ PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH

Task Overview:
🐍 Snake Game using SFML in C++
This project is a classic Snake Game built using C++ and the SFML (Simple and Fast Multimedia Library). It demonstrates fundamental game development principles such as real-time rendering, keyboard input handling, object movement, collision detection, and audio-visual feedback. Designed to be simple yet engaging, this version of the Snake Game also includes sound effects, score tracking, and an increasing difficulty system.

🎮 Game Overview
The Snake Game is a grid-based survival game where the player controls a snake that grows longer each time it eats food. The objective is to keep the snake alive as long as possible by avoiding collisions with the wall or its own body. As the score increases, the snake moves faster, making the game progressively more challenging.

✅ Key Features
Smooth Snake Movement: Controlled via arrow keys (Up, Down, Left, Right) with no immediate reverse direction allowed.

Food Generation: Red circular food appears at random locations, rewarding the player with increased length and score.

Collision Detection: Game ends if the snake hits the wall or itself.

Score Display: Current score is displayed on-screen and updates in real-time.

Restart Option: Press 'R' to restart the game after a game-over state.

Sound Effects:

Eating food plays a munch sound (eat.wav)

Collision plays a game-over sound (gameover.wav)

Background Music: Loops continuously during gameplay (background.ogg).

Progressive Speed: Snake speed increases slightly with each food consumed, enhancing difficulty.

🧠 Concepts Demonstrated
Object-Oriented Programming (OOP): Encapsulated in a SnakeGame class with clean methods for logic separation.

Event Handling: Real-time keyboard interaction using SFML's event system.

2D Graphics Rendering: Drawing shapes (RectangleShape, CircleShape) for snake segments and food.

Game Timing: Controlled using SFML’s Clock and Time classes to manage movement speed.

Sound & Music Integration: Utilizes Sound, SoundBuffer, and Music classes for an immersive experience.

🗂 File Structure
bash
Copy
Edit
assets/
├── arial.ttf            # Font for score and game-over text
├── eat.wav              # Sound effect when food is eaten
├── gameover.wav         # Sound effect when game ends
└── background.ogg       # Looping background music

main.cpp                 # Contains the SnakeGame class and main loop
▶️ How to Run
Install SFML (v2.5 or higher).

Place main.cpp and assets/ in the same directory.

Compile using:

bash
Copy
Edit
g++ main.cpp -o snake_game -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
Run:

bash
Copy
Edit
./snake_game
📌 Future Improvements
Add levels or stages.

Introduce obstacles and power-ups.

Save and load high scores.

Touchscreen or mobile compatibility.

Animated snake and better sprite support.

📜 License
This project is open-source and free to use for educational or personal use. Contributions are welcome!

OUTPUT-
![Image](https://github.com/user-attachments/assets/8dc2bb43-8d1f-413b-939b-3865ee4dc366)
