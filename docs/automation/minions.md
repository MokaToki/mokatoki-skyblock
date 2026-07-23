# 🤖 Minions System

Automate your island's resource generation and processing using **Minions**! These helper NPCs perform automated tasks, allowing you to generate income and materials even while busy building.

---

## 📜 Minion Commands

Use the following commands to manage and buy minions:

| Command | Alternative | Description |
| :--- | :--- | :--- |
| `/minion` | `/minions` | Opens the main Minion management GUI dashboard. |
| `/minion store` | - | Opens the in-game Minion Store to purchase new minions using in-game currency. |

---

## ⚙️ How Minions Work

### 🛠️ Minion Types
There are five specialized types of minions available to automate your island:

* ⛏️ **Miner**
    * Automatically mines ore and stone generators placed in front of it.
* ⚔️ **Slayer**
    * Automatically kills mobs that spawn or are channeled in front of it.
* 🪓 **Lumberjack**
    * Automatically cuts down trees and logs within its working radius.
* 🧑‍🌾 **Farmer**
    * Automatically plants, grows, and harvests crops in its farming field.
* 🎣 **Fisher**
    * Automatically fishes in a designated adjacent water source.

### 📦 Inventory & Chest Linking
Minions do not have an internal inventory. To collect and save the resources they generate, you must link them to an external chest:

* **Requirement:** Place a chest within **30 blocks** of the minion.
* **Mechanism:** Open the minion's GUI, select the chest-link tool, and click on the chest you want to link.
* **Important:** If no chest is linked, all items harvested or collected by the minion will drop directly onto the ground.

### 🍖 Feeding & Health
Minions start with **0 Health** when placed and must be fed before they can begin working.

* **Energy depletion:** Minions consume energy and lose health as they work. If their health drops to 0, they will stop working.
* **Healing via Food:** Right-click the minion while holding food items (such as Bread, Apples, Steak, or Golden Apples) to restore their health.
* **Healing via GUI:** Open the minion's GUI and pay a small fee in in-game currency to heal them instantly.

### 🎒 Placing & Picking Up
* **Placing:** Place the minion item down on a block like any other placeable object.
* **Pickup:** Simply **Left-click** the minion to return it to your inventory as an item. Any linked chest configuration is preserved when placing it back down.
