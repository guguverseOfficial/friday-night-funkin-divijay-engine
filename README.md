# 🐱 DIVIJAY ENGINE

> **“Undertale was made on GameMaker, and I’m making Divijay Engine. Why would you doubt this engine?!”**

Welcome to **Divijay Engine** — the most meme‑filled, the lightest, and the craziest engine for rhythm games (inspired by Friday Night Funkin').

I created this engine to prove that you don’t need gigabytes of junk to make a cool game. There’s no tons of unnecessary scripts, heavy video libraries, or boring standard characters here. Just you, music, arrows, and **a cat in glasses**.

---

## 🚀 Why Divijay Engine?

*   **💾 Ultra‑lightweight**: Forget about 500 MB engines. Divijay Engine weighs next to nothing and runs smoothly even on weak laptops.
*   **😎 Memetic vibe**: Easter eggs, secrets, and the Cat who isn’t drunk — that’s just how it is.
*   **🛠️ Full mod support**: You can create your own songs by simply dropping JSON files and music into the `mods` folder.
*   **⚡ Made with GameMaker**: The same engine that Undertale was made with.

---

## 📦 How to play?

1. Download the latest release of Divijay Engine (the `.exe` file).
2. Launch the game.
3. Press **Enter** (or click the button) to start.
4. If you have a `mods` folder with songs, the engine will pick them up automatically!

---

## 🛠️ How to create your own mod (Mod Template)

Creating mods for Divijay Engine is easy. You don’t need to be a programmer.

1. Create a `mods` folder next to `Divijay Engine.exe` (if it doesn’t exist).
2. Inside, create a folder for your mod (for example, `MyAwesomeMod`).
3. Inside the mod folder, create the following structure:

```text
MyAwesomeMod/
├── mod_info.json        (Mod information)
├── charts/
│   └── song1.json       (Your chart with notes)
├── audio/
│   └── Inst.ogg         (Music)
└── images/
    └── background.png   (Song background)
