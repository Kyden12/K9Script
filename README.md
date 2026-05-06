# 🐕 K9 Menu Script (FiveM)

## 📌 Overview

The K9 Menu Script is a modern NUI-based system that allows players to spawn and control a K9 unit directly in-game. It features a clean, transparent UI with smooth interactions and reliable focus handling to prevent cursor issues.

---

## ✨ Features

* 🐶 Spawn / Despawn K9
* 🚶 Follow & 🔴 Stay commands
* 🔍 Search functionality
* ⚔️ Attack command
* 🚗 Enter / 📦 Exit vehicle
* 🎯 Clean modern UI (no black background)
* 🖱️ Proper cursor handling (no stuck mouse)
* ⌨️ ESC key & button close support

---

## 📁 Installation

1. Drag the `k9_menu` folder into your server's `resources` directory
2. Add this line to your `server.cfg`:

   ```
   ensure k9_menu
   ```
3. Restart your server

---

## 🎮 Usage

* Type `/k9` in-game to open the menu
* Click buttons to control your K9
* Press **ESC** or **Close** to exit the menu

---

## ⚙️ Customization

You can easily:

* Edit button styles in `style.css`
* Add new actions in `client.lua`
* Modify UI layout in `index.html`

---


## 📌 Notes

* This script currently prints actions to console; integrate with your K9 system logic as needed
* Works standalone but can be adapted for frameworks like QBCore or ESX

---

## 🚀 Future Improvements

* Draggable UI
* Animations (fade/scale)
* Full AI-driven K9 behavior
* ox_lib integration

---

## 📄 License

Don't Claim as your own script, Other then that feel free to make changes in the "Config.cfg"

---
