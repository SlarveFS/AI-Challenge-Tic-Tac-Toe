# AI Challenge Tic-Tac-Toe

### Tic-Tac-Toe in SwiftUI against an AI opponent that's hard to beat

Built in **2023**. A clean SwiftUI game following the **MVVM** architecture: the view only renders state, the view model owns the game logic, and the AI decides its moves with a priority strategy (win if possible, block the player's winning move, take the centre, otherwise a random free square).

![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white) ![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?logo=swift&logoColor=white)

![Gameplay recording](https://github.com/BENOITSLARVE98/AI-Challenge-Tic-Tac-Toe/assets/38895100/d8ca8ace-a0f7-461f-8170-f8cdb0502b31)

## How it's built

| File | Role |
|---|---|
| `GameView.swift` | SwiftUI board; disables input while the AI is thinking |
| `GameViewModel.swift` | Game state, turn handling, win and draw detection, and the AI move logic |
| `Alerts.swift` | Win, loss and draw alerts with a rematch action |

## Running it

Open `AI Challenge Tic Tac Toe.xcodeproj` in Xcode and run on an iOS simulator.

---

Built by **Slarve Benoit** · [@SlarveFS](https://github.com/SlarveFS)
