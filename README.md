# NTHU I2P Project: Flappy Bird

**Team Members**: SCLemon, Kian, Mengzhe  
**[Game Proposal (PDF)](https://github.com/SCLemon/NTHU_I2P_Project/blob/main/Final%20Project%20Proposal.pdf)**  

---

## Project Overview

The **Flappy Bird** game is designed with the bird fixed on the x-axis and moving along the y-axis. To simplify implementation, pipes move from right to left.  

### Additional Features:
- Randomized pipe lengths and positions.
- Game-ending events when collisions occur.  

### Assets Source:
- [ianitow/flappy-bird-game (GitHub)](https://github.com/ianitow/flappy-bird-game/tree/main/images)  

### References:
1. [ianitow/flappy-bird-game (GitHub)](https://github.com/ianitow/flappy-bird-game)
2. [Flappy Bird Clone Tutorial (YouTube)](https://www.youtube.com/watch?v=fDdwCTbZL5c)
3. [C++ Game Tutorial (YouTube)](https://www.youtube.com/watch?v=b6A4XHkTjs8&t=896s)
4. [Allegro Tutorial (YouTube)](https://www.youtube.com/watch?v=27G-2-wn41w&t=2202s)

---

## Task Division

- **Part 1 (SCLemon)**:
  - Main structure.
  - Makefile creation.
  - Asset integration.
  - Program initialization.

- **Part 2 (Kian)**:
  - Audio-visual design.
  - User controls.
  - Character setup.

- **Part 3 (Mengzhe)**:
  - Obstacle logic.
  - Event handling for key presses.
  - Character collision events.

---

## Features

1. **Persistent High Score**:
   - The highest score is saved locally in a file and loaded when the game restarts.
   - If a new high score is achieved, the file updates automatically.

2. **Error Handling with `must_init`**:
   - Ensures the program halts with an error message if a critical operation fails, minimizing user-side issues.

3. **Buffered Graphics Rendering**:
   - Double buffering prevents graphical glitches and improves performance.

---

## Customization Options

1. **Screen Scaling**: Adjust screen size by modifying **line 68**.
2. **Pipe Gap**: Change the gap size between pipes at **line 383**.
3. **Score Unit**: Update the scoring system at **line 433**.
4. **Character Properties** (Not Recommended): Modify character settings between **lines 369-373**.

---

## Development Log

- **2023.06.02**: Initial discussion on the project topic.  
- **2023.06.03**:
  - Collected assets (Mario/Flappy Bird).
  - Discussed and rejected alternate proposals (e.g., 2048, as it didn’t align with the theme).
  - Tentative topic chosen: Flappy Bird.  
- **2023.06.07**:
  - Proposed Tetris as an alternative but finalized Flappy Bird.
  - Started development.  
- **2023.06.07~2023.06.08**:
  - Completed Part 1 features and annotations (SCLemon).  
- **2023.06.10~2023.06.11**: Discussed and drafted the project proposal.  
- **2023.06.11**:
  - Completed Parts 2 and 3 features and annotations (Kian/Mengzhe).  
- **2023.06.14~2023.06.15**: Learned about writing effective game proposals.  
- **2023.06.16**:
  - Uploaded to GitHub.
  - Divided responsibilities for writing the proposal.
  - Finalized and uploaded the proposal.  
- **2023.06.19**: Demoed the project.

---

## How to Play

1. Download the repository as a ZIP file.  
2. Extract the folder and open it in VS Code.  
3. Open a terminal and navigate to the `flappy/src` directory:  
   ```bash
   cd flappy/src
