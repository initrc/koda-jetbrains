# Koda Dark Theme for JetBrains IDEs

A sleek, minimalist dark theme for JetBrains IDEs (IntelliJ IDEA, WebStorm, PyCharm, CLion, GoLand, Rider, RustRover, DataGrip, Android Studio, etc.), ported from Neovim's popular [koda.nvim](https://github.com/oskarnurm/koda.nvim) theme.

This theme styles both the **IDE Appearance (UI Theme)** and the **Editor Color Scheme**, with full support for both the **New UI** and **Classic UI**.

---

## 🎨 Color Palette & Design

| Element | Color Code | Description |
| :--- | :--- | :--- |
| **Background** | `#181818` | Deep primary background for editor and windows |
| **Panel Background** | `#141414` | Sidebar, tool windows, popups, and status bar |
| **Foreground / Text** | `#b0b0b0` | Standard code text, parameters, and identifiers |
| **Strings & Characters** | `#cccccc` | Crisp, bright string literals and characters |
| **Emphasis / Special** | `#cccccc` | High-contrast keywords (e.g. `return`), titles, active tabs |
| **Keywords & Types** | `#777777` | Subdued keywords, types, control flow, and operators |
| **Functions & Methods** | `#d9ba73` | Warm golden accent for function/method declarations & calls |
| **Constants & Numbers** | `#d9ba73` | Numbers, booleans, and constant literals |
| **Comments & Line Numbers** | `#50585d` | Unobtrusive comments and gutter line numbers |
| **Active Line / Selection** | `#272727` | Caret row highlight and selection backgrounds |
| **Borders & Separators** | `#474747` | Subtle contrast window and panel borders |
| **Info / Links** | `#8ebeec` | Diagnostics info, links, and breadcrumbs |
| **Success / Added** | `#86cd82` | VCS additions, passing test runs |
| **Warning / Modified** | `#d9ba73` | VCS modifications, warnings |
| **Danger / Errors** | `#ff7676` | Errors, syntax issues, VCS deletions |

---

## 📦 Installation

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

## 💻 Integrated Terminal

The built-in JetBrains terminal colors are configured to match the Koda dark 16-color ANSI palette defined in `koda-dark.toml`.
