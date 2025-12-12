# Catthode for Windows Terminal

> **From CRT to OLED.** Bringing warmth back to a world of cold themes.

Catthode is a high-contrast, retro-futuristic theme designed for prolonged coding sessions. It blends the crushed blacks of modern OLED displays with the comforting, warm glow of analog tungsten filaments.

## 🎨 Color Palette

### Surface
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Base** | `#000000` | Editor background, pure void |
| **Sidebar** | `#141414` | Sidebars, panels, widgets |
| **Selection** | `#2d2d2d` | Text selection, hover states, buttons |
| **Border** | `#636363` | Borders, subtle dividers |

### Phosphor
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Text** | `#ffffff` | Standard text |
| **Variable** | `#e8e8e8` | Variables, identifiers |
| **Comment** | `#b3b3b3` | Comments, docstrings |
| **Ignored** | `#757575` | Ignored files, disabled elements |

### Glow
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Wheat** | `#fae2c8` | Types, classes, bright glow |
| **Tan** | `#d9b98c` | Secondary glow |
| **Gold** | `#ffb86c` | Keywords, storage, headers |
| **Amber** | `#ff9e3b` | Functions, accents, active states |
| **Clay** | `#f08d49` | Operators, punctuation |

### Accents
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Red** | `#ff6b6b` | Errors, deletions, dangerous actions |
| **Green** | `#b9d665` | Strings, insertions, success |
| **Cyan** | `#aee6d6` | Regex, escapes, information |
| **Blue** | `#9cd9e6` | Links, properties, secondary info |
| **Purple** | `#eba4be` | Constants, numbers, booleans |

## 📦 Installation

1.  **Open Windows Terminal**.

2.  Click the dropdown arrow in the title bar and select **Settings** (or press `Ctrl+,`).

3.  Click **Open JSON file** at the bottom left (or access the `settings.json` manually).

4.  Find the `"schemes"` array in your `settings.json`.

5.  **Copy and paste** the content of `catthode.json` into the `"schemes"` array.

    ```json
    "schemes": [
        {
          "background": "#000000",
          "black": "#000000",
          "blue": "#9CD9E6",
          "brightBlack": "#636363",
          "brightBlue": "#9CD9E6",
          "brightCyan": "#AEE6D6",
          "brightGreen": "#B9D665",
          "brightPurple": "#EBA4BE",
          "brightRed": "#F08D49",
          "brightWhite": "#E8E8E8",
          "brightYellow": "#D9B98C",
          "cursorColor": "#FAE2C8",
          "cyan": "#AEE6D6",
          "foreground": "#FFFFFF",
          "green": "#B9D665",
          "name": "Catthode",
          "purple": "#EBA4BE",
          "red": "#FF6B6B",
          "selectionBackground": "#636363",
          "white": "#B3B3B3",
          "yellow": "#FFB86C"
        },
        // ... other schemes
    ]
    ```

6.  **Save** the file.

7.  Go back to **Settings** > **Profiles**. Select your default profile (e.g., PowerShell or Command Prompt).

8.  Go to **Appearance** > **Color scheme** and select **Catthode**.

9.  Click **Save**.
