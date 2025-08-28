# 🎨 Bash Color Code Reference Utility

<p align="center">
  <a href="https://github.com/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER.svg?style=for-the-badge" alt="Contributors">
  </a>
  <a href="https://github.com/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER/network/members">
    <img src="https://img.shields.io/github/forks/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER.svg?style=for-the-badge" alt="Forks">
  </a>
  <a href="https://github.com/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER/stargazers">
    <img src="https://img.shields.io/github/stars/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER.svg?style=for-the-badge" alt="Stargazers">
  </a>
  <a href="https://github.com/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER/issues">
    <img src="https://img.shields.io/github/issues/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER.svg?style=for-the-badge" alt="Issues">
  </a>
  <a href="https://github.com/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER?style=for-the-badge" alt="License">
  </a>
  <br>
  <img src="https://img.shields.io/badge/language-Shell-black.svg?style=for-the-badge" alt="Language">
  <img src="https://img.shields.io/badge/Made%20with-Bash-1f425f.svg?style=for-the-badge" alt="Made with Bash">
  <img src="https://img.shields.io/badge/maintainer-LINUX--OASIS-blueviolet?style=for-the-badge" alt="Maintainer">
</p>

<p align="center">
  A comprehensive visual reference for ANSI escape codes in Bash. This script demonstrates various methods for coloring and styling terminal text and, most importantly, prints the raw escape code for each example, allowing developers to easily copy and paste them into their own scripts.
</p>

---

## ✨ Features

This script is a one-stop shop for exploring terminal color and style capabilities:

*   🎨 **Predefined Variables**: A list of common colors with their variable names and raw codes.
*   🌈 **256-Color Palette**: Full demonstration of the 8-bit foreground and background color palettes.
*   ✍️ **Text Styles**: See examples of **Bold**, *Italic*, `Blinking`, and `Underlined` text combined with the 256-color palette.
*   💎 **24-bit "True Color"**: See the power of 16 million colors with a smooth gradient and a continuous color ribbon.
*   📋 **Copy-Paste Ready**: Every color and style example is printed with its raw escape code for immediate use in your projects.
*   📚 **Reference Tables**: Quick lookup tables for standard colors, styles, and a breakdown of the ANSI escape sequence syntax.

## 📸 Screenshots

*(A GIF demonstrating the script's output would be highly effective here!)*

**Predefined & 256-Color Foreground Demo:**
```
Displaying Predefined Colors:
Light Red [[ VAR: fLightRed, CODE: \e[91m ]]
Light Green [[ VAR: fLightGreen, CODE: \e[92m ]]
...

Displaying 256 Foreground Colors:
Syntax: \e[38;5;<0-255>m
  example text here   [[ COLOR:: \e[38;5;0m ]]
  example text here   [[ COLOR:: \e[38;5;1m ]]
...
```

**24-bit True Color Gradient:**
```
Displaying a 24-bit True Color Gradient (with codes):
   # [[ BG: \e[48;2;255;0;0m, FG: \e[38;2;255;0;0m ]]
   # [[ BG: \e[48;2;239;16;0m, FG: \e[38;2;239;16;0m ]]
...
```

## 🖥️ Compatibility

This script is designed to be highly portable and should run on most modern Linux systems. It has been tested and is known to be compatible with:

*   Debian
*   Ubuntu
*   Linux Mint
*   Other Debian-based derivatives
*   Any Linux distribution that uses a modern `bash` shell and a terminal emulator that supports ANSI escape codes (most terminals do!).

## ⚙️ Dependencies & Installation

This is a self-contained Bash script with **no external dependencies**. You do not need to install any packages.

The script does not attempt to install any software on your system.

### Installation

1.  Clone the repository or download the script.
    ```sh
    git clone https://github.com/LINUX-OASIS/BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER.git
    cd BASH-ANSI-COLOR-ESCAPE-SEQUENCE-DISPLAYER
    ```
2.  Make the script executable:
    ```sh
    chmod +x ./custom-COLOR-CODES-BASH-ESCAPE-SEQUENCE-COLOR.sh
    ```

### Usage

Simply run the script from your terminal:
```sh
./custom-COLOR-CODES-BASH-ESCAPE-SEQUENCE-COLOR.sh
```

---

## 💬 Contributing

Pull requests, issues, and suggestions are warmly welcomed!
See `CONTRIBUTING.md` for guidelines.

## 🌐 Links

*   **Issues**
*   **Pull Requests**
*   **Releases**
*   **Wiki**

## 📜 License

This project is licensed under the **GNU General Public License v3.0**. See the LICENSE file for details.

## 🧙‍♂️ Maintainer

**LINUX-OASIS**
