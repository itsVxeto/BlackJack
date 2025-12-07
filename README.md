# BlackJack
A simple version of BlackJack written in C.

## 📌 Features

- Single-player game against the Dealer.
- Standard 52-card deck, shuffled randomly.
- Automatic handling of **Aces** (1 or 11 points).
- Player turn with options:
  - **Hit** → draw a new card
  - **Stand** → keep the current score
- Dealer turn is automatic (draws until reaching at least 17 points).
- Initial **Blackjack** check.
- Determines winner according to standard rules.
- Option to **play multiple rounds** without restarting the program (but keep asking the player's name).

---

## 🎮 How to Play

1. The player and dealer are dealt 2 cards each.
2. The dealer shows only the **first card** (hiding the second one).
3. The player chooses between **Hit** or **Stand**:
   - `H` → draw another card
   - `S` → stop
4. The dealer draws cards until reaching at least 17 points.
5. Winner:
   - Over 21 → automatic loss
   - Closer to 21 without exceeding → wins
   - Tie → dealer wins
6. If either the player or dealer gets **21 with the first two cards**, it's **Blackjack** and the game ends immediately.

---

## 🧩 Deck and Card Values

- The deck contains **52 cards** (1–13 for each of the 4 suits).  
- Number cards (2–10) are worth their number of points.  
- Face cards (J, Q, K) are worth **10 points**.  
- Ace (`A`) can be worth **11 or 1**, depending on the total score to avoid busting.  

---

## 📝 How to Run (and Compile if you want)

The game is already compiled, so you can start it by clicking the `BlackJack.exe`.  
If you want to compile it yourself, make sure you have a C compiler installed (e.g., `gcc`).

### Compilation
```bash
gcc blackjack.c -o BlackJack.exe
./BlackJack.exe
```
---

📄 License

This project is licensed under the MIT License.
You can use, modify, and redistribute it freely, as long as you keep the attribution.
See `LICENSE` for more detail.


