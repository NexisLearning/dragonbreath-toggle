# DragonBreath-Toggle

A lightweight Minecraft plugin that allows server admins to enable or disable dragon breath mechanics. On some clients, like **Eagler**, dragon breath can cause crashes—this plugin fixes that by giving you full control.

---

## Description
DragonBreathToggle is designed for Minecraft 1.12 servers. It lets you safely manage dragon breath attacks to prevent client crashes, improve gameplay balance, or customize minigames. You can use either commands or a simple GUI to toggle dragon breath on or off.

---

## How It Works
- The plugin listens for dragon breath events in the world.  
- Using commands or the GUI, admins can enable or disable dragon breath in real time.  
- Changes take effect immediately, no server restart required.  
- Prevents crashes on clients like **Eagler**, where dragon breath sometimes causes errors.

---

## Supported Minecraft Versions
- 1.12  
*(may work on other 1.12.x versions but not guaranteed)*

---

## Installation Instructions
1. Download the latest `DragonBreathToggle.jar` from the Releases section.  
2. Place the `.jar` file in your server's `plugins` folder.  
3. Restart the server or run `/reload` to enable the plugin.  
4. Configure settings (if any) in the `config.yml` generated in the `plugins/DragonBreathToggle/` folder.

---

## Commands & GUI

### Commands
- `/dragonbreath toggle` – Enables or disables dragon breath.  
- `/dragonbreath gui` – Opens the graphical interface for toggling dragon breath.

### DragonBreath GUI
- Displays current dragon breath status (ON/OFF).  
- Click the button to enable or disable dragon breath immediately.  
- Especially useful for admins or staff who prefer visual controls.

---

## Permissions

- `dragonbreath.toggle` – Allows using `/dragonbreath toggle`.  
- `dragonbreath.gui` – Allows opening the dragon breath GUI.  
*(Assign these to admins or trusted staff.)*

---

## Contributing
Feel free to fork the repo and submit pull requests. Issues, suggestions, and feature requests are welcome!

---

## License
[MIT License](LICENSE)
