🏆 Ultimate Auction Simulator

A real-time, multiplayer auction strategy game where players compete to win valuable items while managing a limited purse. Features advanced AI bots, fairness detection algorithms, and live strategy suggestions.

🎮 Play Now
(Click here to test the Simulator)[https://aryanthecuber.github.io/Auction-Bidding-Simulator/]

✨ Features

🧠 Smart AI Bots

Challenge 7 unique AI personalities in Single Player mode:

Incremental: Standard bidder, low risk.

Aggressive: Bids high and fast to intimidate.

Conservative: Only bids on low-value items relative to purse.

Passive: Low activity, easy to beat.

Adaptive: Changes strategy based on remaining budget and time.

Sniper: Waits until the last few seconds to place a winning bid.

Rapid: High-frequency bidder designed to apply pressure.

⚔️ Multiplayer Mode

Real-time Syncing: Uses Firebase Realtime Database to sync bids and game state instantly across devices.

Host Controls: The room creator controls the settings (Category, Round Duration, Number of Rounds).

Live Room Codes: Easy invite system using unique generated room codes.

⚖️ Fairness & Mechanics

Anti-Sniping Protocol: Bids placed in the final 5 seconds automatically extend the timer by 10 seconds to ensure everyone has a fair chance to react.

Smart Minimum Increment: Bids must increase by at least 2% of the item's Base Price to prevent penny-pinching delays.

Consecutive Bidding Prevention: Players cannot bid against themselves if they are already the highest bidder.

Fairness Engine: Logic that validates funds and bid amounts before processing to prevent impossible bids.

📊 Analytics & Insights

Live AI Analysis: Real-time sidebar updates showing the "Most Aggressive" player and the "Big Spender" of the match.

Strategy Insights: The game analyzes your playstyle and offers specific advice (e.g., "Save your funds", "Bid now to intimidate").

Match History: A detailed table at the end of the game shows the winner, sold price, and item details for every round played.

🛠️ How it Works

The entire application is built in a Single HTML File for easy portability, containing:

HTML5/CSS3: For the responsive UI, animations, and Dark Mode (using Tailwind CSS).

Vanilla JavaScript: Handles the game loop, AI logic, and DOM manipulation.

Firebase SDK: Handles authentication and real-time networking.

📜 License

This project is open source and available for educational purposes.
