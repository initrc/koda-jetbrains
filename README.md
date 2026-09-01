# Koda Dark Theme for JetBrains IDEs

A sleek, minimalist dark theme for JetBrains IDEs (IntelliJ IDEA, WebStorm, PyCharm, CLion, GoLand, Rider, RustRover, DataGrip, Android Studio, etc.), ported from Neovim's popular [koda.nvim](https://github.com/oskarnurm/koda.nvim) theme.

This theme styles both the **IDE Appearance (UI Theme)** and the **Editor Color Scheme**, with full support for both the **New UI** and **Classic UI**.

---

## Color Palette & Design

The original Koda color palette has a very high contrast. This theme reduces it by replacing
- text of #ffffff to #cccccc
- background of #101010 to #181818

---

## Installation

### Method 1: Install from Disk (Recommended & Fastest)

1. Open your JetBrains IDE (IntelliJ IDEA, WebStorm, PyCharm, etc.).
2. Go to **Settings / Preferences** (`⌘,` on macOS or `Ctrl+Alt+S` on Windows/Linux).
3. Navigate to **Plugins**.
4. Click the **⚙️ (gear icon)** at the top right of the Plugins window and select **Install Plugin from Disk...**.
5. Choose `dist/koda-jetbrains-1.0.0.zip`
6. Restart the IDE or apply when prompted.
7. Go to **Settings -> Appearance & Behavior -> Appearance** and select **Koda Dark** under **Theme**.
8. Verify **Settings -> Editor -> Color Scheme** is set to **Koda Dark**.

---

### Method 2: Build & Run from Source

To test the theme in a sandbox IDE:
```bash
./gradlew runIde
```

To build a fresh distribution package:
```bash
./gradlew buildPlugin
```
The output file will be generated in `build/distributions/koda-jetbrains-1.0.0.zip`.

---

## Integrated Terminal

iTerm2 and Alacritty colorschemes can be found in `colorscheme/`
