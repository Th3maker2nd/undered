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

Lore

Long before the rise of kingdoms and the birth of war, the land of Undered flourished as a realm of magic-infused nature, where the soil itself pulsed with energy. From the very first dawn, people lived by tilling the earth, nurturing crops, and crafting tools that merged nature and magic into one.

This wasn’t a world of conquerors or warlords. It was a world of life, love, and survival, where every person carved their own path—some through the gentle care of the land, others through the fierce clash of battle.

In Undered, every soul is given a piece of land to call their own. Dedicating themselves to harvesting enchanted crops, trading, and growing their homes into thriving estates. Others become raiders, seeking adventure beyond their borders, claiming what they can through strategic raids and duels.

Yet, most people are neither wholly farmer nor warrior. Instead, they walk the path between both—nurturing their fields by day, defending their land by night.

A well-tended farm isn’t just a place of sustenance; it’s a source of power. The crops of Undered are rich in magical energy, each with unique enhancements for weapons and armor:

Emberfruit – Infuses weapons with fire, leaving enemies scorched.

Moonbloom – Bestows the power of light magic, healing wounds.

Stormroot – Channels electric energy, stunning foes in battle.

Verdant Vine – Grants enhanced stamina, allowing for faster attacks.


Through careful cultivation, a farmer can forge powerful weapons and spells, shaping their destiny in both trade and battle.


---

🏘 The Towns of Undered

Though the world is vast, life revolves around four great towns, each with its own culture, trades, and legends. These towns serve as market hubs, gathering places, and sanctuaries, where duels can be challenged, goods can be exchanged, and love can be found.

Everhollow – Known for its healing springs and magic-infused crops.

Ironroot – Home to fierce warriors and battle arenas, where PvP duels thrive.

Solmere – A bustling town of traders built by craftsmen and scholars, where the marketplace dictates power 

Duskridge – A hidden village where rare magical seeds and monsters can be found.


---

💞 Love, Bonds, and Shared Destiny

In Undered, a life well-lived is not lived alone. Amid the daily struggles, friendships are forged, rivalries are born, and love blossoms.

Court and marry another player or NPC to merge lands and grow stronger together.

Strengthen relationships with townsfolk for exclusive trades, secret spells, and alliances.

Duel for honor, not just war—some battles are fought to prove worth, to impress a lover, or to settle a score.


A strong heart is just as powerful as a strong sword.


---

⚔️ The Balance of Harmony and Chaos

For all its beauty, Undered is not without conflict. Farms must be protected, and raiders lurk in the shadows, seeking resources to claim as their own.

But balance is the way of the world. Those who take too much without giving back find their lands cursed, their soil turned barren by the ancient forces that watch over Undered. Those who tend to their land, forge relationships, and respect the cycle of life will prosper beyond measure.

Will you cultivate, conquer, or walk the path between?


---

🌎 Your Journey in Undered

You wake up in your small cottage, surrounded by a single plot of land, the scent of morning dew heavy in the air. The world is waiting.

You can:
🏡 Grow your farm into a thriving estate, trading in magical resources.
⚔️ Master turn-based combat, battling players and defending your land.
💑 Fall in love, share your life, and build something greater together.
🌍 Explore the towns, forge alliances, and shape the future of Undered.

Your story begins now.

🌿 Will you build, battle, or love? In Undered, the choice is yours.



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

