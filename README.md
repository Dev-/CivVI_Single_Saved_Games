![Civ VI Banner](/img/image.png)

# Civ VI Single Player Saved Games

This repository stores **Civilization VI** single-player save files, allowing you to sync your game progress between Windows and macOS.

## Setup & Usage

### On Windows
1. **Initialize/Clone Repository:**
   - If initializing:
     ```powershell
     cd "C:\Users\Sean\Documents\My Games\Sid Meier's Civilization VI\Saves\Single"
     git init
     git remote add origin https://github.com/Dev-/CivVI_Single_Saved_Games.git
     ```
   - If cloning:
     ```powershell
     git clone https://github.com/Dev-/CivVI_Single_Saved_Games.git .
     ```

2. **Sync Saves:**
   - Before playing: `git pull`
   - After playing:
     ```powershell
     git add .
     git commit -m "Update save files on [date]"
     git push
     ```

### On macOS
1. **Clone Repository:**
   ```bash
   cd "~/Library/Application Support/Sid Meier's Civilization VI/Saves/Single"
   git clone https://github.com/Dev-/CivVI_Single_Saved_Games.git .
