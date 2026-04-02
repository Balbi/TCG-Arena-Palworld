# Palworld OCG mod for TCG Arena

> This is an unofficial mod for TCG Arena that allows you to play the Palworld Official Card Game.

---

## 📚 Table of Contents
- [Playing Instructions](#how-to-start-playing)
- [Rules for Playing](#rules-for-playing)
- [Contribution Instructions](#contribution-instructions)
- [Testing Instructions](#testing-instructions)
- [License](#license)

---

## How to Start Playing

1. Go to the game link [here](https://tcg-arena.fr/load/aHR0cHMlM0ElMkYlMkZiYWxiaS5naXRodWIuaW8lMkZUQ0ctQXJlbmEtUGFsd29ybGQlMkZHYW1lX1BhbHdvcmxkLmpzb24=).
2. Click "Add game"
3. Select "Palworld Official Card Game" from the dropdown list at the top
4. Go to "Decks"
5. Click "Create deck"
6. Name your deck (something like "Demo Deck" is fine)
7. Click Import
8. Paste the Decklist (found [here](#demo-deck-list))
9. Click "Save"

### How to Play
1. Make sure "Palworld Official Card Game" is selected at the top of the screen
2. Click "Play"
3. Either Copy your **id** or paste an id that was sent to you to connect
4. Once both players are in, click the Play icon on the left
5. Click the "Start" button
6. Select your deck you want to play from the dropdown list
7. Click "Continue"
8. Look at your hand, and click "Keep hand and start"
9. Play the game 🙂

Notes:
* You can group cards if you are moving a Pal to a Structure. While holding "G" on your keyboard, click the Pal then the Structure, release "G"
* Every turn after the first turn, Souls are played and a card is drawn automatically

### Demo Deck List
```
4 Relaxaurus
4 Pengullet
4 Jormuntide Ignis
4 Chillet
4 Cattiva
4 Lamball
4 Grizzbolt
4 Chikipi
4 Foxparks
2 Reckless Charge
4 Single-Shot Rifle
2 Pump-Action Shotgun
2 Mounted Machine Gun
4 Primitive Furnace
10 Soul
```

---

## Rules for Playing

### PHASES

On each player's turn, they will go through 5 phases:

#### Stand Phase (automatic)

- Stand all tapped cards controlled by the player (untap)

#### Draw Phase (automatic)

- Draw 1 card (skip this if it is your first turn and you are playing first)

#### Soul Phase (automatic)

- Draw 2 Souls from the Soul Deck and place in your Soul Area (if you are going second, on your first turn you draw 1 additional Soul)

*Note: If you are going first, you will have to draw 2 Souls manually in TCG Arena*

#### Main Phase
In any order, you may do the following:
- Deploy a Pal, Structure, or Gear from hand to base
- Use an event from hand
- Battle using a standing (untapped) Pal in your base
- Use "ACT Ability" of cards in your base
- Rest 3 standing Souls to draw 1 card from the top of your deck (once per turn)

*Note: During your opponent's main phase, you may play **Quick** cards*

*Note: If you went first, you cannot attack on your first turn*

#### End Phase 
- Heal all damage on Pals

------------------------------

**MULLIGANS**
- TBD

---

## Contribution Instructions

Contributions are welcome. Follow these steps to keep changes consistent.

### How to Contribute
1. Fork the repository.
2. Create a feature branch:
  ```bash
  git checkout -b feature/<short-description>
  ```
3. Commit changes with clear messages:
  ```bash
  git commit -m "Add: short summary of change"
  ```
4. Push your branch:
  ```bash
  git push origin feature/<short-description>
  ```
5. Open a Pull Request.

### Contribution Standards
- Keep changes focused and small.
- Update documentation when behavior changes.
- Follow project style/conventions.
- Test changes before submitting.

### Pull Request Checklist
- [ ] Documentation updated
- [ ] No unrelated changes included
- [ ] Clear PR description

---

## Testing Instructions
Coming soon.

---

## License
This project is licensed under the [MIT License](LICENSE.md).