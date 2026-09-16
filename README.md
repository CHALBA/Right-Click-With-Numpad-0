# Right-Click-With-Numpad-0

A lightweight AutoHotkey automation script to open the context menu by pressing Numpad 0 at the mouse pointer position, eliminating the need to physically right-click.

## 🚀 Features
- **Effortless Context Menu:** Press **Numpad 0** to trigger a right-click right where your mouse cursor is.
- **Smart Num Lock Handling:** Works perfectly whether your **Num Lock** is ON or OFF.
- **No Mouse Struggle:** Great for opening images in a new tab or checking context options without using the mouse right-click button.

## 🛠️ How to Use

### Prerequisites
Make sure you have [AutoHotkey](https://autohotkey.com) installed on your Windows PC.

### Installation & Running
1. Copy the script code below:
```autohotkey
; Works when Num Lock is ON
Numpad0::
Click, Right
return

; Works when Num Lock is OFF
NumpadIns::
Click, Right
return
```
2. Create a new text file on your PC, paste the code, and save it as `RightClick.ahk`.
3. Double-click the `RightClick.ahk` file to run it.
4. Move your mouse over any image or page element and press **Numpad 0**!

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
