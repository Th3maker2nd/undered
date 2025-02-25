# Undered - A Multiplayer Fantasy Farming & Combat Game

Undered is a 2D multiplayer farming simulation blended with elements from Skyrim, Pokémon, and Clash of Clans, set in a fantasy world where players manage their farmland, engage in turn-based combat, explore towns, and battle for resources.


---

🌍 Game Overview

Core Gameplay

🌾 Farm Simulation – Grow crops, expand your farmland, and generate income.

🏰 Town Exploration – Trade in the marketplace, interact with NPCs, and take on quests.

⚔️ Turn-Based Combat – Engage in Pokémon-style battles with weapons, spells, and potions.

🏹 PvP & PvE Battles – Challenge players to duels or fight against AI enemies.

🛡 Plot Raids – Attack farms to steal crops and resources, defend your own with security upgrades.

🔥 Weapon Enhancements – Craft powerful spell-infused weapons using farmed resources.

🏠 Customization – Build, upgrade, and protect your property.

🌎 Multiplayer Networking – Trade, battle, and raid farms in a persistent online world.



---

🎮 Gameplay Features

🏡 Farm Management & Economy

Players start with a small farmland and one farming grid.

Grow crops, sell them in the marketplace, or use them for weapon enchantments.

Upgrade farmland to unlock more grids, livestock, and rare plants.

Hire security to prevent raids from stealing resources.


⚔️ Turn-Based Combat System (Pokémon Style)

Players take turns attacking, defending, or using items.

Actions include:

Attack (Use weapons or spells)

Defend (Reduce incoming damage)

Use Item (Heal, buff, or debuff)


Spells are tied to weapons and require mana or stamina.

Players request battles in town – no random attacks.


🏹 PvP & Raids (Clash of Clans Style)

Players can raid other farms to steal crops and resources.

Defend your farm by upgrading security:

Guard NPCs

Defensive spells

Fortifications


Attackers must win a turn-based battle to steal resources.


🛡 Weapons & Spell Enchantments

Weapons include: Swords, Bows, Wands, Shields, and Staves.

Spell Enchantments:

Fire Enhancement – Burn enemies over time

Ice Enhancement – Slow enemy actions

Nature Enhancement – Leech enemy HP


Craft enhancements using crops and rare materials.


🏙 Marketplace & Trading

Buy and sell crops, weapons, and enhancements.

Dynamic player-driven economy.

Players can trade directly or use the marketplace.


💞 Relationships & Marriage System

Players can build relationships with NPCs or other players.

Marriage provides:

Shared farmland

Bonus income

Unique couple buffs in battle



🌎 Multiplayer & Blockchain (SUI Integration)

Decentralized Economy – Game assets are tokenized on SUI.

On-Chain Trades – Marketplace transactions are secure and transparent.

PvP Raids & Battles – Stored on the blockchain for fairness.



---

🛠 Tech Stack

Game Development

Python (Pygame for 2D rendering)

Asyncio (Handling multiplayer networking)


Networking & Multiplayer

WebSockets (Real-time interactions)

Flask/Django Backend (Server for matchmaking, PvP, and marketplace)


Blockchain & Economy

SUI Blockchain (Asset ownership, marketplace transactions)

Solidity/MOVE Contracts (On-chain asset tracking)



---

📜 Lore & Worldbuilding

In the land of Undered, the world is divided between peaceful farmers and war-hardened raiders.
Ancient magic lies within the land, infused into crops, granting powerful enchantments to those who harvest them.

The Kingdom of Valmere has fallen, leaving towns to fend for themselves. Players must choose their path:

Will they cultivate their farm, trading resources to build wealth?

Will they raid rival farms, seeking dominance through battle?

Or will they explore the world, mastering ancient magic and challenging champions?


The choice is yours in Undered.


---

📂 Project Structure

Undered/
│── assets/               # Sprites, sound effects, UI elements  
│── game/                 # Core game logic  
│   │── engine.py         # Game loop and event handling  
│   │── player.py         # Player class (farming, combat)  
│   │── weapons.py        # Weapon class & spells  
│   │── combat.py         # Turn-based battle logic  
│   │── farm.py           # Farming grid and upgrades  
│   │── marketplace.py    # Trading and economy system  
│   │── networking.py     # Multiplayer WebSockets  
│── server/               # Multiplayer game server  
│   │── app.py           # Flask/Django API  
│   │── database.py      # Stores player data, battles, marketplace  
│── blockchain/           # SUI smart contracts  
│── ui/                   # Game menus, HUD, in-game UI  
│── README.md             # Project Documentation


---

🚀 Getting Started

1️⃣ Clone the Repository

git clone https://github.com/yourusername/Undered.git
cd Undered

2️⃣ Install Dependencies

pip install pygame flask websockets sui-sdk

3️⃣ Run the Game

python game/engine.py

4️⃣ Run the Server (For Multiplayer)

python server/app.py


---

📌 Roadmap

Phase 1: Core Gameplay

✅ Player movement & farming grid
✅ Basic combat system
✅ PvP requests & turn-based battles
✅ Inventory & weapons

Phase 2: Multiplayer & Economy

🔲 Implement raids & farm security
🔲 Add marketplace trading
🔲 Deploy assets to SUI Blockchain

Phase 3: Exploration & Expansion

🔲 Expand the town & NPC quests
🔲 Introduce boss battles & dungeons
🔲 Allow player housing & land expansion


---

💡 Contributing

Want to help build Undered? Feel free to:

Submit pull requests

Report bugs

Suggest new features



---

📜 License

Undered is an open-source project under the MIT License.


---

🌟 Join the Community

💬 Discord: Join Here
🐦 Twitter: Follow Here
📜 Whitepaper: Read Here


---

🔥 The Future of Undered

Undered is more than a game – it’s a living world where farming meets combat, where raids determine power, and where the economy is driven by player interactions on SUI.

Are you ready to build, battle, and thrive?

🚀 Start your journey today!

