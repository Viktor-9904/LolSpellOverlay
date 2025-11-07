# League of Legends Summoner Spell Overlay

A lightweight **League of Legends overlay** built using Windows Presentation Foundation (WPF) to display and countdown enemy summoner spell cooldowns.  

> This project was created as a **personal WPF practice project** to learn and experiment with building desktop applications.


<p align="center">
  <img src="README/preview.png" alt="App Preview" width="200"/>
</p>

---

## ⚠️ Disclaimer

This overlay does **not inject or modify the game**.
**The developer is not responsible** for any issues, penalties, or account suspensions that may occur while using this software.  
### **_Use at your own discretion._**

---

## 🎮 Controls

- **Left Click:**  
  - If the spell is not on cooldown → set cooldown  
  - If already on cooldown → reduce cooldown by 1 second  

- **Right Click:**  
  - If spell is on cooldown → remove cooldown  

- **Ctrl + Left Click:**  
  - Removes active cooldown and cycles to the **next spell**  

- **Ctrl + Right Click:**  
  - Removes active cooldown and cycles to the **previous spell**

---

## 📝 Planned Features

- Add an checkbox for **_Ionian Boots_** to accurately calculate summoner spell haste.
- Add an checkbox for **_Cosmic Insight_** to accurately calculate summoner spell haste.
- Allow assigning the **_enemy player level_** to accurately calculate **Unleashed Teleport** cooldown.
- Play a **_sound effect_** shortly before an enemy summoner spell becomes available.


---

## 💻 Requirements

- Windows 10 or 11  
- [.NET 9 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)  
---

## 🚀 Installation
1. Clone the repository:
```bash
git clone https://github.com/Viktor-9904/LolSpellOverlay.git
```
2. Navigate to the solution’s build output folder. By default, Visual Studio places the compiled files here:
```bash
LolSpellOverlay\bin\Debug\net9.0-windows\
  ```
3. Locate the executable:
```bash
LolSpellOverlay.exe
```
4. Double-click **LolSpellOverlay.exe** to run the application.
---

## 💡 Notes

- Works best when **League of Legends is in borderless/windowed mode**.
- The overlay **will not appear in exclusive fullscreen mode** due to Windows limitations.
- The application runs completely **offline** and does not require an internet connection.

---

## 📜 License

This project is licensed under the **MIT License**


