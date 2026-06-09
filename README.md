<p align="center">
  <h1 align="center">The Neat Sheet</h1>
  <p align="center">
    <strong>A curated collection of tips, tricks, and tools for engineers who love efficiency.</strong>
  </p>
  <p align="center">
    <a href="#-windows">Windows</a> &bull;
    <a href="#-command-line">Command Line</a> &bull;
    <a href="#-web-tools">Web Tools</a> &bull;
    <a href="#-contributing">Contributing</a>
  </p>
</p>

---

## Why This Exists

We've all had that moment — a coworker shows you a shortcut or a tool and you think, *"How did I not know about this?"* This is a living document of those moments. Bookmark it, share it, contribute to it.

---

## <kbd>Windows</kbd>

### Keyboard Shortcuts

> Power-user shortcuts that save time every single day.

| Shortcut | What It Does |
|:---------|:-------------|
| <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>V</kbd> | **Paste as plain text** — strips all formatting. Works in most apps. |
| <kbd>Win</kbd> + <kbd>V</kbd> | **Clipboard history** — scroll through everything you've copied recently. *(Enable on first use.)* |
| <kbd>Ctrl</kbd> + <kbd>Arrow Keys</kbd> | **Jump between words** in text fields. Add <kbd>Shift</kbd> to select as you go. |
| <kbd>Ctrl</kbd> + <kbd>Esc</kbd> | **Open Start menu** — handy if your keyboard lacks a Windows key. |
| <kbd>Win</kbd> + <kbd>L</kbd> | **Lock workstation** instantly. Walk away with confidence. |
| <kbd>Win</kbd> + <kbd>Shift</kbd> + <kbd>S</kbd> | **Screenshot tool** — snip any region of your screen to clipboard. |
| <kbd>Win</kbd> + <kbd>.</kbd> | **Emoji picker** — quickly insert emoji and special characters. |
| <kbd>Alt</kbd> + <kbd>Tab</kbd> | **Switch windows** — hold Alt and tap Tab to cycle through open apps. |

### Run Commands (<kbd>Win</kbd> + <kbd>R</kbd>)

> Quick-launch these without ever touching the Start menu.

| Command | What It Opens |
|:--------|:--------------|
| `mstsc` | Remote Desktop Connection |
| `appwiz.cpl` | Programs & Features (Add/Remove Programs) |
| `ncpa.cpl` | Network Connections |
| `devmgmt.msc` | Device Manager |
| `diskmgmt.msc` | Disk Management |
| `services.msc` | Services console |

### Recommended Tools

| Tool | Description |
|:-----|:------------|
| [AltSnap](https://github.com/RamonUnch/AltSnap) | Hold <kbd>Alt</kbd> + drag to move any window. <kbd>Alt</kbd> + right-drag to resize. Linux-style window management on Windows. |
| [PowerToys](https://github.com/microsoft/PowerToys) | Microsoft's official power-user toolkit — FancyZones, Color Picker, File Rename, and much more. |
| [Everything](https://www.voidtools.com/) | Instant file search across your entire system. Blazing fast. |

---

## <kbd>Command Line</kbd>

### General Shell Tips

| Tip | Description |
|:----|:------------|
| `!!` | Re-run the last command (bash/zsh). Great with `sudo !!`. |
| `Ctrl` + `R` | Reverse-search your command history. |
| `Ctrl` + `L` | Clear the terminal screen (same as `clear`). |
| `cd -` | Jump back to the previous directory. |

### Useful One-Liners

```bash
# Find large files (>100MB) in current directory tree
find . -type f -size +100M -exec ls -lh {} \;

# Kill a process using a specific port
lsof -ti :3000 | xargs kill -9

# Quick HTTP server in current directory
python3 -m http.server 8080
```

---

## <kbd>Web Tools</kbd>

> Bookmark-worthy sites that solve real problems.

| Site | What It Does |
|:-----|:-------------|
| [whatsmydns.net](https://www.whatsmydns.net) | **DNS propagation checker** — see how your records resolve from servers worldwide. |
| [ipchicken.com](https://www.ipchicken.com) | **Public IP lookup** — your external IP at a glance. |
| [explainshell.com](https://explainshell.com) | **Shell command explainer** — paste any command and get a breakdown of every flag. |
| [crontab.guru](https://crontab.guru) | **Cron expression editor** — visualize and build cron schedules with ease. |
| [regex101.com](https://regex101.com) | **Regex tester** — build, test, and debug regular expressions interactively. |
| [jsoncrack.com](https://jsoncrack.com) | **JSON visualizer** — paste JSON and see it as an interactive graph. |

---

## <kbd>Contributing</kbd>

Found something neat? Contributions are welcome!

1. Fork this repository
2. Add your tip, tool, or trick to the appropriate section
3. Open a Pull Request with a brief description

**Guidelines:**
- Keep entries concise — one or two sentences max
- Include a link if referencing a tool or website
- Make sure it's something that would genuinely surprise or help another engineer

---

<p align="center">
  <sub>Licensed under <a href="./LICENSE">GPL-3.0</a></sub>
</p>
