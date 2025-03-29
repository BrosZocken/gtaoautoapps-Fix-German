# GTA Online Apartments Trade-In Exploit Script

This is an automated script (AHK, v1.1 for now) for using the apartments trade-in exploit in GTA Online.

---

## Table of Contents
1. [WARNING](#warning)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [IMPORTANT](#important)
5. [Controls](#controls)
6. [NOTES](#notes)
7. [Known Bugs](#known-bugs)
8. [Planned Improvements](#planned-improvements)

---

## WARNING
I take **no responsibility** for any bans, suspensions, or other consequences resulting from the use of this script.  
Every user applies this script **at their own risk**.

---

## Requirements
For this to work, you need:
1. **GTA5 E&E (Enhanced & Expanded)** version of the game (ATM it **DOESN'T WORK** on Legacy Edition),
2. Game set to `1024x768` windowed mode,
3. Game's language set to **English**,
4. Safezone size set to **7 ticks**:
   - Go to `Settings > Display`, set it to max (all the way to the right), then tap left three times,
5. Phone alerts set to **OFF** and Message Frequency set to **1 hour**:
   - Go to `Settings > Notifications`,
6. Frame Limit set to **60 fps** and Pause Game on Focus Loss set to **OFF**:
   - Go to `Settings > Graphics`,
7. "Snapmatic Quick Launch" set to **OFF**:
   - Pull up the phone while in GTA Online, press the right arrow until you reach the "settings" tile, enter it, then go to "Snapmatic" and choose "Snapmatic Quick Launch OFF",
8. Spawn Location set to any building **except**:
   - Apartments, Garages, or entity-packed locations like LS Car Meet (examples: Hangar, Facility, Kosatka, Auto Shop).

---

## Installation
1. Download the [`.zip`](https://github.com/tetriskillerh/gtaoautoapps-Fix/releases/latest) file and extract it (you need to install AutoHotKey v1.1 to use the script),  
   or  
2. Download the [`.exe`](https://github.com/tetriskillerh/gtaoautoapps-Fix/releases/latest) file (no installation required, but you cannot customize the hotkeys in the .exe version).

**IMPORTANT**
-
The Script will ask for admin rights.

**Steuerung:**
-
**P**: VORBEREITUNGSPHASE
- Dies dient dazu, alle 10 Slots auf einen Wert von jeweils $550k einzustellen. Sie MÜSSEN dies im Story-Modus ausführen. Starten Sie es und warten Sie, bis es abgeschlossen ist.

**O**: RÜCKZAHLUNGSPHASE
- Dies ist der Haupt-Hotkey. Sie verwenden ihn, um "Apartments zu verkaufen" (wenn alle Slots eingestellt sind). Sie MÜSSEN diesen Hotkey im Story-Modus ausführen. Ein Fenster mit einer Eingabebox erscheint. Geben Sie ein, wie viele Durchläufe Sie versuchen möchten, und warten Sie, bis es abgeschlossen ist.

**Numpad2**: No-Save aktivieren "Panikknopf"
- Sie können dies verwenden, um den NoSave-Modus manuell zu aktivieren.

**Numpad3**: No-Save deaktivieren "Panikknopf"
- Sie können dies verwenden, um den NoSave-Modus manuell zu deaktivieren.

**L**: Neuladen "Panikknopf"
- Verwenden Sie dies, um das gesamte AHK-Skript neu zu laden/"zurückzusetzen".

**-**: Beenden "Panikknopf"
- Verwenden Sie dies, um das Skript vollständig zu beenden.

Sie können die Hotkeys nach Belieben anpassen.

### **Numpad6**: Cycle Slow Mode  
- This hotkey cycles through different delay options for Slow Mode.  
- The delay cycles through `0ms`, `50ms`, `100ms`, ..., up to `300ms`.  
- Use this if the script frequently fails during tasks like selecting apartments or navigating the web browser, such as accidentally opening Legendary Motorsport instead.  
- **Tip:** Holding `Numpad6` for more than 500ms will immediately reset the delay to `0ms`, without needing to cycle through all options.
- **Default:** `0ms` (disabled).

### **Numpad9**: Toggle NoSave Status Display  
- Toggles the display of the NoSave status.  
- When enabled, a tooltip will show whether NoSave Mode is active or inactive.
- Use this to visually monitor the NoSave state.
- **Default:** `off`.

---

## NOTES
- Feel free to change hotkeys to your own preferences (if using the `.ahk` version).
- If you encounter issues, ensure all requirements are met and admin rights are granted.
- Before creating a new issue, please check the [Known Bugs](#known-bugs) section to see if the problem is already documented.

---

## Known Bugs
- None

---

## Planned Improvements
- **Customizable Hotkeys in `.exe` Version:** Add support for changing hotkeys directly in the `.exe` version.
- **Enhanced Debug Mode:** Provide more detailed logs for troubleshooting.
- **Multi-Language Support for Script Menus:** Allow users to choose the language for script popups and menus (e.g., the prompt asking for the number of runs).
