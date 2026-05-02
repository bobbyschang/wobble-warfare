# 🟢 Wobble Warfare

A blob survival game co-created by **Bear** (Bobby) and **GitHub Copilot**.

## About the Game

Wobble Warfare is an HTML5 canvas game where you play as a brave blob armed with a sword, fighting off endless waves of zombies. Survive as long as you can, earn XP, level up, and upgrade your equipment to become the ultimate blob warrior.

Every 10 waves, a powerful zombie boss appears — a massive purple blob wielding a mace with more health, more damage, and a devastating charge attack.

## How to Play

Open `index.html` in any modern browser — no install required.

### Controls

| Action | Key / Input |
|--------|-------------|
| Move | **WASD** or **Arrow Keys** |
| Aim sword | **Mouse** |
| Slash | **Left Click** |
| Open Shop | **B** |
| Start / Restart | **Click** on title or death screen |

### Game Mechanics

- **HP Bar** — displayed top-left. If it reaches 0, you die and must restart.
- **Wave Counter** — shown top-right. Tracks how many waves you've survived.
- **XP & Leveling** — kill zombies to earn XP. Level up to earn money.
- **High Score** — your best wave survival is saved locally across sessions.

### Shop (press B)

Spend your hard-earned money on upgrades between waves or after dying:

| Item | Effect |
|------|--------|
| ⚔️ Sword | More damage, longer reach, stronger knockback |
| 🛡️ Shield | Blocks a percentage of incoming damage |
| ❤️ Health+ | Increases your maximum HP |
| 🔄 Auto-Slash | Sword swings automatically without clicking |
| 🔫 Gun | Ranged weapon that shoots at nearby zombies |

All items are upgradeable through multiple tiers — invest wisely!

### Boss Fights

Every 10 waves, a **Zombie Boss** spawns:
- Larger size with significantly more HP
- Deals extra damage
- Wields a weapon and charges at you
- Grants bonus XP when defeated

## Tech

- Pure HTML5 + Canvas + vanilla JavaScript
- Single-file game (`index.html`) — no dependencies
- High scores stored in `localStorage`

---

*Have fun slashing!* 🗡️
