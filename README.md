# MegaMillions/Powerball Game

A lottery simulation game built using **C#**. This project allows users to simulate both MegaMillions and Powerball lottery draws. Users can switch between the two games, input numbers, and generate random results. The extra number for each game is generated according to the rules of the respective lottery (MegaMillions or Powerball).

## Features
- **Simulates both MegaMillions and Powerball** lottery draws.
- Allows users to switch between MegaMillions and Powerball modes.
- Generates and compares user-selected numbers with randomly generated winning numbers.
- **Extra number generation**: MegaMillions extra number max is 25; Powerball extra number max is 26.
- Tracks and displays the number of **wins** and **losses**.
- Clear result display, showing whether the user has won or lost.

## Technologies Used
- **C#**
- **Windows Forms** for user interface design.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MegaMillions-Powerball-Game.git
   ```
2. Open the project in **Microsoft Visual Studio**.
3. Navigate to **Solution Explorer**, right-click the solution, and select **Build**.
4. Once built, click **Start** (or press **F5**) to run the game in Debug mode.

## Gameplay Instructions
1. **Select a game**: Choose either **MegaMillions** or **Powerball** by selecting the appropriate radio button.
   - MegaMillions: Numbers range from 1 to 70, and the extra number ranges from 1 to 25.
   - Powerball: Numbers range from 1 to 69, and the extra number ranges from 1 to 26.
2. **Click "Draw"**: The game will generate a random set of user numbers and compare them against randomly generated winning numbers.
3. **View Results**: The game will display both the user's numbers and the winning numbers, along with a win/loss result.
4. **Track Your Progress**: The game keeps track of the number of wins and losses in real-time.

## Future Improvements
- Add functionality to track user plays over time and analyze win/loss statistics.
- Implement more detailed odds calculations for each game mode.
- Enhance the graphical interface for improved usability and aesthetics.

## Contributions
Feel free to fork this repository, submit issues, or make pull requests to contribute to the project!

---
