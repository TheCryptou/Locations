# 📍 Location

**Location** is a lightweight Minecraft Spigot/Paper plugin designed for **solo survival worlds**.  
It lets you record, view, and track your own waypoints — without teleportation or cheats.  
The goal is to keep it simple, immersive, and always up to date with the latest Minecraft versions.

---

## ⚙️ Features

### Main Commands
- `/location add <name>`  
  Saves your current position with the chosen name (only shows **X/Z** coordinates for an extra bit of challenge).

- `/location list`  
  Displays all saved locations with their names and coordinates.

- `/location remove <name>`  
  Removes a saved location.

- `/location follow <name>`  
  Shows a **directional arrow** and the **distance** to the selected location in your action bar.  
  The display updates automatically when you move or turn.

- `/location unfollow`  
  Stops the current follow session.

---

## 🧠 Technical Details
- All locations are stored in a simple **YAML** file.  
- The **follow system** runs on a lightweight scheduler that updates only when the player moves.  
- Only **X/Z** coordinates are used — no teleporting, keeping exploration authentic.  
- Fully optimized for **solo play**, minimal performance impact.

---

## 🧩 Compatibility
- Works on **Spigot** and **Paper** servers.  
- Tested on **Minecraft 1.21.6/8**.  
- No external dependencies required.

---

## 🔄 Maintenance
I actively maintain and update this plugin to keep it compatible with the latest Minecraft versions and improve its overall performance and stability.

---

## 📜 License
This plugin is open-source.  
You’re free to use, modify, and share it — just remember to **credit the original author**.
