# Video Poker

A browser-based Video Poker game that simulates the popular casino game with multiple variants.

![NVIDIA_Overlay_2MBj2E2nPE](https://github.com/user-attachments/assets/31c13a69-2e68-4b55-ba6f-b03217f0b54c)


## 🎮 Features


- **Multiple Game Variants**: Play different versions of Video Poker including:
  - Jacks or Better (default)
  - Tens or Better
  - All American
  - 9/5 Jacks or Better
  - 8/6 Jacks or Better
  - 8/5 Jacks or Better
  - 7/5 Jacks or Better
  - 6/5 Jacks or Better
- **Responsive Design**: Works on desktop and mobile devices
- **Theme Switching**: Toggle between light and dark themes
- **Realistic Gameplay**: Authentic Vegas-style video poker rules and payouts
- **Customizable Betting**: Adjust your bet size before each hand

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/varunbudati/VideoPoker.git
cd VideoPoker
```

2. Open `index.html` in your web browser.

That's it! No build process or additional dependencies required.

## 📖 How to Play

1. **Start a New Game**: The game begins with 1000 chips and a default bet of 10.
2. **Adjust Your Bet**: Use the + and - buttons to increase or decrease your bet before dealing.
3. **Deal Cards**: Click the "DEAL" button to receive your initial 5 cards.
4. **Hold Cards**: Click on any cards you want to keep. Selected cards will be marked "HOLD".
5. **Draw New Cards**: Click the "DRAW" button to replace the cards you didn't hold.
6. **Win or Lose**: Your hand will be evaluated, and any winnings added to your balance.
7. **Continue Playing**: Click "DEAL" to start a new hand.

## 💰 Paytable

The paytable shows your potential winnings per bet unit. Actual payout depends on your current bet.

| Hand Type | Payout (Jacks or Better) |
|-----------|--------------------------|
| Royal Flush | 800 |
| Straight Flush | 50 |
| Four of a Kind | 25 |
| Full House | 9 |
| Flush | 6 |
| Straight | 4 |
| Three of a Kind | 3 |
| Two Pair | 2 |
| Jacks or Better | 1 |

*Note: Payouts vary based on the selected game variant.*

## 🎲 Game Variants

Different variants offer different paytables:

- **Jacks or Better**: The classic version where pairs of Jacks or higher pay.
- **Tens or Better**: Lower threshold where pairs of Tens or higher pay.
- **All American**: Higher payouts for Straights, Flushes, and Full Houses.
- **X/Y Variants**: Different payout ratios where X is the payout for Full Houses and Y is the payout for Flushes.

## 🧩 Project Structure

- `index.html`: Main HTML file
- `css/style.css`: Styling for the game
- `js/videopoker-gui.js`: Game logic and functionality

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/amazing-feature`)
3. Commit your Changes (`git commit -m 'Add some amazing feature'`)
4. Push to the Branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

- **Varun Budati**
  
---

Enjoy the game and good luck! 🍀
