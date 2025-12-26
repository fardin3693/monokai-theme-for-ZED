# Monokai Classic for Zed

A beautiful, dark theme for the [Zed](https://zed.dev) editor, inspired by the iconic [Monokai Pro](https://monokai.pro/) aesthetic from VS Code. This theme brings the classic, high-contrast color palette to Zed's high-performance interface.

<img width="1365" height="737" alt="Screenshot_1" src="https://github.com/user-attachments/assets/150b33af-e6a4-42e5-8a38-323a63f53990" />

<img width="1365" height="696" alt="image" src="https://github.com/user-attachments/assets/b7b2d7cb-3ff3-48c2-80cb-1e9a5d6a5038" />

<img width="1365" height="669" alt="image" src="https://github.com/user-attachments/assets/19f1e98c-fdfa-44a3-83ef-76298909f365" />



## 🎨 Features

- **Classic Monokai Palette:** Features the beloved `#272822` background and vibrant syntax highlighting.
- **High Contrast:** Designed for readability with distinct colors for functions, strings, keywords, and comments.
- **UI Integration:** Custom styling for the panel, terminal, status bar, and active line highlights.
- **Multi-Cursor Support:** Distinct colors for active players/cursors.

## 🚀 Installation

To use this theme in Zed, follow these simple steps:

### Method 1: Manual Installation (Recommended)

1.  Open Zed and go to **Zed** > **Open Settings** (or press `Cmd + ,` on macOS / `Ctrl + ,` on Linux/Windows).
2.  In the file explorer sidebar, look for the `themes` folder. If it doesn't exist, create a new folder named `themes` inside your Zed configuration directory:
    - **macOS:** `~/.config/zed/themes`
    - **Linux:** `~/.config/zed/themes`
    - **Windows:** `%APPDATA%\Zed\themes`
3.  Inside the `themes` folder, create a new folder named `monokai-classic`.
4.  Create a file named `monokai-classic.json` inside that folder and paste the [theme JSON](./monokai-classic.json) into it.
5.  Reload Zed (`Cmd + Shift + R` or `Ctrl + Shift + R`).
6.  Open the Command Palette (`Cmd + Shift + P` / `Ctrl + Shift + P`) and type `Theme: Monokai Classic`.

### Method 2: Via Settings JSON

Alternatively, you can append the theme JSON directly to your `settings.json` file under the `"themes"` array, though creating a separate file is cleaner.

## 🎨 Color Palette

| Role | Color |
| :--- | :--- |
| **Background** | `#272822` |
| **Foreground** | `#fdfff1` |
| **Keywords** | `#f92672` |
| **Functions** | `#a6e22e` |
| **Strings** | `#e6db74` |
| **Constants/Numbers** | `#ae81ff` |
| **Types/Classes** | `#66d9ef` |
| **Parameters** | `#fd971f` |
| **Comments** | `#6e7066` |

## 📝 License

This theme is inspired by the original Monokai. Please check the [LICENSE](./LICENSE) file for details.

## 👤 Credits

- **Original Concept:** Monokai
- **Ported to Zed by:** Fardin


Enjoy coding in Monokai Classic! If you like this theme, please consider ⭐ starring the repository.
