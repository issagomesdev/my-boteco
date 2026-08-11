<h1>🍻 MY BOTECO</h1>

![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-PC-green?style=for-the-badge)
![Status](https://img.shields.io/badge/🛠️%20In%20Development-FF8C00?style=for-the-badge)


<p align="center">
  <img src="https://media.byissa.dev/my-boteco/preview.webp" alt="Game Preview" width="600"/>
</p>

**My Boteco** is a real-time bar management simulator where players must quickly serve customers to maximize satisfaction. Focused on speed and strategy, players prepare drinks and food, earning experience points (XP) and improving the bar's reputation. Every decision impacts success, making efficient and fast service essential.

[![🎮 Play here](https://img.shields.io/badge/🎮%20Play%20here-My%20Boteco-blueviolet?style=for-the-badge)](https://my-boteco.byissa.dev)

<h2>🧭 Index</h2>

<p>
  • <a href="#gameplay">🧩 Gameplay</a><br/> 
  • <a href="#roadmap">🚧 Roadmap</a><br/>
  • <a href="#tech-stack">🛠️ Tech Stack</a><br/>
  • <a href="#how-to-run">🚀 How to run</a><br/>
  • <a href="#author">🧑‍💻 Author</a><br/>
</p>

<h2 id="gameplay">🧩 Gameplay</h2>

### ▶️ Start The Day

- The player starts by approaching a blue apron on the counter, triggering an instruction to press `X` to begin.

- This spawns a few customers at tables.

### 🧾 Collect Orders

- By approaching a table and pressing `X`, the player collects the orders.

- Orders appear in a container at the top-right corner of the screen.

- Currently, only drinks are implemented.

- Drinks have id, name, preparation time, and a sprite.

- Orders consist of up to 5 random drinks, tied to a table number.

- The order UI includes drink names, table number, total prep time (+60s buffer), and a countdown timer.

### 🥤 Prepare Drink

- The player approaches the drinks in counter and presses X to open the drink menu.

- Drinks are shown with icons and names in a horizontal list.

- The player uses [→] to navigate, Enter to select and confirm.

- A progress bar appears showing remaining prep time.

- Once completed, the drink is added to the inventory batch on the right.

<h2 id="roadmap">🚧 Roadmap</h2>

### ✅ Implemented

- 👤 Player with basic movement

- 🏠 Bar-style scenario

- 🧾 Drinks menu

- 🧊 Interactive items in the environment (counter, tables)

- 🍹 Ordering system with random drinks (up to 5 per order)

- 📦 Interface with order container and remaining time

- 🍽️ Drink preparation via interaction and modal menu

- ⏳ Progress bar for preparation time

- 📥 Inventory lot where prepared drinks are stored

### 🔄 Planned

- 📘 Interactive tutorial at the beginning of the game

- 🧍‍♂️ New sprites of various customers

- 🚶‍♂️ Animation of customers entering the door and going to the tables

- 🍔 Inclusion of meals and desserts

- 🧅 Ingredient system for drinks and food

- 🔁 Simultaneous preparation queue for items

- 🗑️ Options to discard, store or deliver prepared items

- 🔼 Levels with progressive difficulty (time, items, customers)

- 😠 Customer mood system (emojis, final evaluation)

- ⭐ XP system with performance evaluation

### 💡 Future ideas

- 📊 Results screen with statistics at the end of each level

- 🏆 Achievements and extra challenges

- 🎵 Ambient soundtrack and sound effects

<h2 id="tech-stack">🛠️ Tech Stack</h2>

- 🎮 Unity (C#)

- 🖼️ Unity UI Toolkit / Canvas

- 🧠 ScriptableObject-based systems


<h2 id="how-to-run">🚀 How to run</h2>

To run **My Boteco** locally, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/issagomesdev/my-boteco.git
   ```
2. **Open in Unity**
   - Launch Unity Hub.
   - Click on **'Open'** and select the project folder you just cloned.
   - Make sure you have Unity version **2022.3.x** or higher (depending on your actual version).
   - Let Unity load and compile the project.

3. **Play the game**
   - Open the `Scenes/Main.unity` scene (or your main scene).
   - Click the **Play** button at the top of the editor.

> ℹ️ If you encounter errors, make sure all necessary packages are installed and your Unity version matches the project requirements.

<h2 id="author">🧑‍💻 Author</h2>

Development by [Issa Gomes](https://github.com/issagomesdev)
Contact us: [LinkedIn](https://linkedin.com/in/issagomesdev) • [Email](mailto:byissag@gmail.com)

