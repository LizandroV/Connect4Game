# Connect Four — Blazor
 
A browser-based Connect Four game built with ASP.NET Core Blazor (.NET 8), following the [Microsoft Learn module](https://learn.microsoft.com/en-us/training/modules/dotnet-connect-four/).
 
## Features
 
- Two-player Connect Four on a 7 × 6 board
- Animated piece drops
- Win, tie, and error detection
- Customizable board and player colors via component parameters
- **Move History panel** — live sidebar showing every move made, newest first
## Getting Started
 
**Prerequisites:** [.NET 8 SDK](https://dotnet.microsoft.com/download)
 
```bash
# Clone or extract the project, then:
cd ConnectFour
dotnet run
```
 
Open your browser at `https://localhost:5001`.
 
## Project Structure
 
```
ConnectFour/
├── Components/
│   ├── Board.razor          # Game board component
│   ├── Board.razor.css      # Board & move history styles
│   └── Pages/
│       └── Home.razor       # Hosts the Board with color parameters
├── GameState.cs             # Game logic + move history tracking
└── Program.cs               # Service registration
```
