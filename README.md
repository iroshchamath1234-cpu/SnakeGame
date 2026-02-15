# Snake Game

A classic Snake game built with Java Swing.

## Features
- Classic snake gameplay
- Score tracking
- Grid-based movement
- Collision detection
- Game over screen

## Controls
- **Arrow Keys**: Control snake direction (Up, Down, Left, Right)

## How to Run in IntelliJ IDEA

1. **Create New Project**
   - Open IntelliJ IDEA
   - File → New → Project
   - Select "Java" and click Next
   - Name your project (e.g., "SnakeGame")
   - Click Finish

2. **Add the Files**
   - In the Project view, navigate to `src` folder
   - Copy `Main.java` and `SnakeGame.java` into the `src` folder

3. **Run the Game**
   - Right-click on `Main.java`
   - Select "Run 'Main.main()'"
   - Or press `Shift + F10`

## How to Run from Command Line

```bash
# Compile
javac Main.java SnakeGame.java

# Run
java Main
```

## Game Rules
- Use arrow keys to control the snake
- Eat red apples to grow longer and increase your score
- Don't hit the walls or your own body
- Try to get the highest score possible!

## Technical Details
- **Language**: Java
- **GUI Framework**: Java Swing
- **Board Size**: 600x600 pixels
- **Grid Size**: 25x25 pixels per unit
- **Initial Snake Length**: 6 units

## Future Improvements
- [ ] Add difficulty levels (speed adjustment)
- [ ] Add pause functionality
- [ ] Add high score tracking
- [ ] Add sound effects
- [ ] Add restart button without closing window

## Screenshot
![Snake Game](screenshot.png)
*Add a screenshot of your game here*

---
Made with ☕ and Java

