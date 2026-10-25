# ⚔️ CodeQuest: The video game programmer's adventure

## 🧙 Chapter 1. The apprentice wizard's path

You have been admitted to the Academy of Arcanists, but before you start you need to train your magic power.

1. Ask for the **wizard's name** and set the initial level to `1`.
2. The training lasts **5 days**. Each day the wizard:
   - meditates a random number of **hours** (random, max 24 h),
   - gains a random amount of **power** between 1 and 10 points (random).
3. Every day, show a message with the **cumulative** evolution:

   ```
   Day 3 → Azrael, you have meditated 10 hours and your power is now 27 points!
   ```

4. At the end, show the **final power level**. Depending on the total:

| Total power | Message | Rank |
|-------------|---------|------|
| `< 20` | "You are retaking the exam in the 2nd call" | Raoden the Elantrian |
| `≥ 20` | "You still confuse the wand with a spoon" | Zyn the Buggy |
| `≥ 30` and `< 35` | "You are a Magic Breeze Summoner." | Arka Nullpointer |
| `≥ 35` and `< 40` | "Wow! You can summon dragons without burning down the lab!" | Elarion of the Embers |
| `≥ 40` | "You have reached the rank of Master of the Arcane!" | ITB-Wizard the Grey |

> 🔍 **TIP:** investigate how to create random numbers with the `Random` class.

---

## 🐉 Chapter 2. RAMón the Mighty's dungeon

Your wizard must prove his training and enter the dungeon of the dragon **RAMón the Mighty**, where every door is protected by a *digital access code*.

- There are **3 doors**. Each one has a random code between **1 and 5**.
- You have **3 attempts per door**.
- If you fail a door, the game ends with the message:

  ```
  The dragon has detected your presence and kicked you out of the server!
  ```

- If you guess the code, this message appears:

  ```
  The dragon respects you. You have unlocked the next level!
  ```

- If you reach the third door and open it successfully, this message appears:

  ```
  You have unlocked the final level. Get ready for the battle!
  ```

> 🔍 **TIP:** nested loops.

---

## 💰 Chapter 3. Loot the mine

You have defeated the dragon and found a mine full of *magic bitcoins*!
Every time you mine, you get a random amount between **5 and 50 bits**, or maybe nothing.
You can only dig **5 times**.

- Show the result of **every excavation**.
- On each excavation there is a chance of finding nothing. If that happens, show this message:

  ```
  Today is not your lucky day, you found 0 bits.
  ```

- If the total is **greater than 200**, show:

  ```
  You have unlocked the golden GPU! Your spells now run at 120 FPS!
  ```

- If in the end you do not reach 200 bits, show:

  ```
  Your magic graphics card is still integrated. Time to defeat another dragon!
  ```
