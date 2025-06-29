# Space Shooter – Two-Player Pygame Battle

A simple, 2D, fast-paced, local two-player space shooter built with **Python** and **Pygame** designed to learn pygame module.

---

## Features

- Bullet firing with sound effects  
- Two-player real-time gameplay  
- Health bar tracking  
- Custom graphics and background  
- Background music & sound effects  
- Game ends when one spaceship wins  

---

## Folder Structure

SpaceShooter/  
├── Assets/  
 ├── spaceship_red.png  
 ├── spaceship_yellow.png  
 ├── space.png  
 ├── Gun+Silencer.mp3  
 └── Grenade+1.mp3  
├── build/  
├── dist/  
 ├── Assets/  
   ...  
├── venv/  
├── firstgame.py  
├── firstgame.spec  
├── requirements.txt  
└── README.md  


---

## How to Run

pip install -r requirements.txt  
python firstgame.py  

 -> Build .exe (Optional- using PyInstaller)
pyinstaller --onefile --noconsole --add-data "Assets;Assets" firstgame.py  
-> Then run the .exe inside the dist/ folder.  
Make sure the Assets folder is copied inside dist/ after building.  

