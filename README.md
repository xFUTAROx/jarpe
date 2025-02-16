# Jarpey - Interactive Emotional Support App

## Overview

**Jarpey** is an interactive desktop application designed to support emotional well-being through the metaphor of a virtual pet. It uses Tkinter for the graphical user interface, SQLite for data persistence, and includes functionalities for:

- **Pet Interaction:** Feed, pat, and rename your pet to increase its happiness.
- **Meditation:** Track meditation sessions which reward you with coins.
- **Mood Diary:** Record daily mood, set personal goals, and review past entries.
- **Chat System:** Engage in simple conversations with Jarpey for emotional support.

## Features

### Pet Management
- Choose from different pet types (Dog, Cat, Bunny, Fox).
- Interact with your pet to influence its mood and happiness.
- Buy and manage food inventory.

### Meditation Timer
- Start and stop meditation sessions.
- Earn coins for each minute of meditation which can be used to buy food for your pet.

### Mood and Goal Tracking
- **Diary:** Record your mood across various aspects (happiness, relationships, stress, etc.) in a three-phase system (Hold, Check, Change).
- **Goals:** Set personal goals, track progress, and mark them as completed.
- **Suggestions:** Receive personalized suggestions based on your mood entries and current goals.

### Chat System
- Simple AI-driven responses based on user input for emotional support.
- Stores chat logs in the diary for later review.

## Installation

To run Jarpey:

1. **Prerequisites:**
   - Python 3.x installed on your system.
   - Tkinter should come pre-installed with Python, but ensure it is available.

2. **Setup:**
   - Clone or download this repository:
     ```bash
     git clone <repository-url>
     ```
   - Navigate to the directory containing the script:
     ```bash
     cd <directory-name>
     ```

3. **Run the Application:**
   - Execute the main script:
     ```bash
     python main.py
     ```

## Usage

- **Start**: Upon running, you'll be prompted to choose and name your pet.
- **Tabs**: Use the tabs at the top to navigate between:
  - **Homepage**: For meditation, goals, and suggestions overview.
  - **PetPage**: To interact with your pet.
  - **Diary**: To record and review your emotional states.

- **Pet Interaction**: 
  - Use buttons to buy food, feed, pat, or rename your pet.
  
- **Meditation**: 
  - Click "Start Meditation" to begin a session. The timer will count up, and you'll earn coins every minute.

- **Mood Diary**: 
  - Navigate to the Diary tab to log your mood, set goals, or review past entries.

- **Chat**: 
  - Enter text in the chat box to converse with Jarpey for emotional support.

## Database Schema

Jarpey uses SQLite with the following tables:
- `meditation_history`: Tracks meditation sessions.
- `inventory`: Manages pet food stock.
- `diary_entries`: Stores daily mood logs and chat entries.
- `goals`: Holds personal goals to achieve.
- `completed_goals`: Records goals that have been met.

## Contributing

Feel free to fork the repository and submit pull requests. For bugs or feature requests, please open an issue on GitHub.

## License

This project is open-source under the MIT License. See the LICENSE file for more details.
