# 🌌 Kerbopause

**Kerbopause** is an expansion mod for *Kerbal Space Program* that introduces a mysterious deep-space boundary world and a distant, frozen planetoid to the extreme outer edge of the star system. 

Confront the cosmic abyss, brave absolute blindness in a crushing vacuum, and journey further into the deep freeze than any Kerbal has gone before.

---

## 🪐 Features

### 🔥 1. Kerbopause (The Boundary World)
* **The Interstellar Gatekeeper:** A massive, terrifying super-Earth of molten slag orbiting at an immense distance of **123 KAU** (Kerbal Astronomical Units) from the Sun.
* **The Sightless Void:** While it glows with a violent, roaring crimson glare from deep space, crossing its threshold plunges all visual feeds, navigation optics, and skyboxes into pitch-black invisibility.
* **The Ultimate Challenge:** Features no atmosphere—meaning no aerodynamic drag to slow you down—just a heavy, crushing 1.4 g gravity well wrapped in absolute darkness.

### 🔴 2. Sedirum (The Outer Frontier)
* **The Sedna Analog:** A tiny, frozen iceball skating along a deeply eccentric, egg-shaped orbit that cuts past the outer perimeter even further out into the void.
* **Ancient Landscape:** Choked with deep-red organic tholins and steep icy mountains.
* **Solar Dead Zone:** Located so far from the sun that solar panels are completely useless, forcing players to rely entirely on RTGs, nuclear power, or life-support generators.

---

## 🛠️ Mod Architecture & Layout

The mod uses **Kopernicus** configuration pipelines to safely inject custom planetary assets without impacting system memory.

```text
GameData/
└── Kerbopause/
    ├── Cache/                 # Computed planetary bin files
    ├── Configs/               # Planet configuration files
    │   ├── Kerbopause.cfg     # The magma sphere framework
    │   └── Sedirum.cfg        # The Sedna analog framework
    └── PluginData/            # Memory-optimised visual maps
        ├── Kerbopause/        # Textures for Kerbopause
        └── Sedirum/           # Textures for Sedirum
```

---

## 🚀 Installation

1. Ensure you have a clean installation of **Kerbal Space Program**.
2. Install the mandatory dependencies:
   * **[Kopernicus Planetary System Modifier](https://github.com)**
   * **[ModuleManager](https://kerbalspaceprogram.com)**
3. Download the latest release of **Kerbopause**.
4. Extract the contents of the download file and drop the `Kerbopause` folder directly into your KSP **`GameData`** directory.

---

## 🖥️ Requirements & Specifications

* **Game Version:** KSP 1.12.x (or any version compatible with your active Kopernicus build)
* **Dependencies:** Kopernicus & ModuleManager
* **Recommended Mods:** HyperEdit or BetterTimeWarp (highly recommended to survive the long journey out to 123 KAU!).

---

## 📄 License & Attribution

This project is licensed under the **MIT License** - see the LICENSE file for details. 
*Created by the Kerbopause development team.*
