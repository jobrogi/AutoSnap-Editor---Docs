# 📐 AutoSnap – Editor Plugin

**AutoSnap – Editor** is a lightweight plugin for Unreal Engine that brings hotkey-based snapping controls to your level design workflow. Easily align actors using a dynamic grid while dragging them in the editor viewport — no need to touch native snapping settings.

Built for speed, flexibility, and modular asset placement.

---

## ✨ Features

- 🔧 Snap while dragging actors (no need to toggle UE's grid)
- ⌨️ Hotkey-based axis control (X/Y/Z snapping)
- 🎯 Realtime grid adjustment with mouse wheel
- 👀 Visual feedback with custom log messages (or grid overlay if enabled)
- 🧠 Axis lock toggles for fine control
- 🧩 Modular and C++-friendly design

---

## 🔧 Installation

1. Drop the plugin folder into your project:


2. Regenerate Visual Studio project files
3. Launch Unreal → Enable **AutoSnap – Editor** under *Edit > Plugins*
4. Restart the editor

---

## 🎮 Editor Hotkeys

| Action                     | Hotkey            |
|---------------------------|-------------------|
| Enable snap on drag       | Hold `Shift` while dragging |
| Toggle snapping globally  | `Shift + G`       |
| Increase snap size        | `Ctrl + Mouse Wheel Up` |
| Decrease snap size        | `Ctrl + Mouse Wheel Down` |
| Toggle X snapping         | `Alt + X`         |
| Toggle Y snapping         | `Alt + Y`         |
| Toggle Z snapping         | `Alt + Z`         |

---

## 🧠 How It Works

- The plugin hooks into actor dragging in the editor
- When the snap hotkey is held (`Shift`), selected actors will snap to a virtual grid while moving
- Snap resolution is adjustable in real-time using the scroll wheel
- You can toggle individual axis constraints (X/Y/Z) for precision

This allows modular asset placement (e.g., walls, props, platforms) with precision **without** relying on Unreal’s built-in snapping.

---

## 🛠 UE Version Support

| Engine Version | Status    |
|----------------|-----------|
| 5.3.x          | ✅ Tested |
