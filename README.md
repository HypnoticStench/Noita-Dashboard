# Noita Dashboard

Hey everyone! 

I have over 2,000 hours in Noita, and I got tired of constantly switching between 10 different tabs when planning a run. I wanted a single, clean "cockpit" for the game, so I built this dashboard. 

It brings together the best community tools into one screen: **Telescope**, **Noitool**, the **Wiki**, and a progress tracker.

## What it does
*   **Seed Sync:** Type your seed and NG+ cycle at the top, and it updates the Telescope map instantly.
*   **Noitool Quick-Link:** A one-click button to copy your current seed and open Noitool (since Noitool doesn't allow iframe embedding).
*   **Live Wiki:** A docked wiki panel so you can check spell stats without leaving the dashboard.
*   **The All Seeing Eye:** A built-in tracker (courtesy of `noita-progress`) to check your spell unlocks and achievements.

## 🔒 A Note on Safety & Privacy

I know sharing save files or using new tools can be scary. Here is how this works:

1. **Your save data never leaves your PC.** The "All Seeing Eye" section uses the excellent `noita-progress` tool. It does not automatically read your save file. Instead, you manually drag and drop your `save00` folder into that panel, and it processes everything 100% locally in your browser. No data is uploaded to me or any server.
2. **The code is completely open.** It's just a single HTML file. You can read every line right here in this repository.
3. **I used AI to help build this.** I'm a gamer, not a web developer. I had the vision for the UI and how it should work, but I used an AI assistant to help write the HTML, CSS, and layout. I'm being upfront about it because transparency is important, and the code is wide open for anyone to inspect.

*(Note: I am looking into building a way to auto-detect your local `save00` folder, but I wanted to get a functional version out first!)*

If you want to run it locally, just download `index.html` and double-click it.

## 🙏 Credits
I just built the wrapper. All the actual heavy lifting and genius coding was done by these incredible people:
*   [Noita Telescope](https://github.com/Lymm37/noita-telescope) by Lymm37
*   [Noitool](https://github.com/TwoAbove/noita-tools) by TwoAbove
*   [Noita Progress](https://github.com/ipeterov/noita-progress) by ipeterov
*   [The Noita Wiki](https://noita.wiki.gg/)

Good luck out there. Don't touch the lava.
