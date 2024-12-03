# 🐢 Turtle Crossing Game

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Segítsd át a teknőst a forgalmas úton! Izgalmas játék Python Turtle grafikával, ahol a játékosnak át kell juttatnia egy teknőst a forgalmas úton, elkerülve az autókat.

## ✨ Jellemzők

- 🚗 Véletlenszerű autóforgalom
- 📈 Szintrendszer
- 🎨 Színes járművek
- 🔄 Növekvő nehézség
- 📊 Szintkövetés
- 💥 Ütközésérzékelés

## 🚀 Telepítés

```bash
git clone https://github.com/namezor90/turtle-crossing.git
cd turtle-crossing
python main.py
```

## 💻 Használat

- ⬆️ Fel nyíl: Teknős mozgatása felfelé
- Cél: Juss át az úton anélkül, hogy autónak ütköznél
- Minden sikeres átkelés után új szint kezdődik
- Az autók gyorsabbak lesznek minden szinten

## 📁 Projekt Struktúra

```
turtle-crossing/
├── main.py         # Fő játék logika
├── player.py       # Játékos teknős
├── car_manager.py  # Autók kezelése
└── scoreboard.py   # Pontszám és szint
```

## 🎯 Játékszabályok

- A teknős csak felfelé tud haladni
- Az autók balról jobbra közlekednek
- Ütközés esetén játék vége
- Minden sikeres átkelés után:
  - Új szint kezdődik
  - Az autók gyorsabbak lesznek
  - A teknős visszatér a start pozícióba

## 🛠️ Fejlesztés

Játék testreszabása konstansokkal:
```python
# car_manager.py
COLORS = ["red", "orange", "yellow", "green", "blue", "purple"]
STARTING_MOVE_DISTANCE = 5
MOVE_INCREMENT = 10

# player.py
STARTING_POSITION = (0, -280)
MOVE_DISTANCE = 10
FINISH_LINE_Y = 280
```

## 📝 Licensz

[MIT](LICENSE)

## 🤝 Közreműködés

1. Fork-old a projektet
2. Hozz létre egy új branch-et (`git checkout -b feature/awesome`)
3. Commit-old a változtatásokat (`git commit -m 'Add awesome feature'`)
4. Push-old a branch-et (`git push origin feature/awesome`)
5. Nyiss egy Pull Request-et

## 👥 Szerzők

- [@namezor90](https://github.com/namezor90)

## 🎮 Jövőbeli fejlesztési lehetőségek

- 🏆 Magas pontszám mentése
- 🎵 Hangeffektek
- 🌈 Több teknős karakter
- 🚙 Különböző járműtípusok
- 💫 Power-up-ok
- 🏁 Különleges pályák
- 🎨 Testreszabható kinézet
- 🌟 Bónusz pontok
- 🔄 Többjátékos mód
