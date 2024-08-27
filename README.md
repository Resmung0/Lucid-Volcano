
<div align="center">

<img src="Images/LV_name_logo.png" />

---

A dark minimalist VS Code theme with a magma touch.
</div>

## 1. Screen

There's two flavours of this theme: **Magma** and **Lava**.
### 1.1 Magma
<div align="center">
<img src="Images/Magma-lucid-volcano.png"/>
</div>

<d>

### 1.2 Lava

<div align="center">
<img src="Images/Lava-lucid-volcano.png"/>
</div>

## 2. Color palette

<div align="center">
  
Palette             | Hex       | RGB           | Preview
---                 | ---       | ---           | ---
Backgroud Black     | `#181B28` | `24 27 40`    |<img src="Images//darkish_black.png" width="30"/>
Frontground Black   | `#1e2031` | `30 32 49`    |<img src="Images//dark_black_2.png" width="30"/>
Popup Black         | `#252234` | `37 34 52`    |<img src="Images//dark_black.png" width="30"/>
Grey                | `#474c60` | `71 76 96`    |<img src="Images//grey.png" width="30"/>
Pink Red            | `#f20d63` | `242 13 99`   |<img src="Images//pink_red.png" width="30"/>
Purple              | `#891fff` | `137 31 255`  |<img src="Images//purple.png" width="30"/>

</div>

## 3. Tech used

* [Theme Studio for VS Code](https://themes.vscode.one/)

## 4. Installation steps

### 4.1 From VS Code

1. Go to extension part on VS Code activy bar;
2. Search for Lucid Volcano theme;
3. Install and **Enjoy!**

### 4.2 Via CLI:

```
code --install-extension marcosgabriel.lucid-volcano
```

# 5. Extras

To make it even prettier, you can make some changes to your `seetings.json` file. First, press `Ctrl + Shift + P`. Then, choose `Preferences: Open User Seetings` and
paste the following information into your `seetings.json` file.

```json
{
  "workbench.colorCustomizations": {
      "notebook.focusedCellBorder":"#f20d63",
      "notebook.focusedEditorBorder": "#f20d63",
  },
  "notebook.cellToolbarLocation": {
      "default": "right",
      "jupyter-notebook": "left"
  },
}
```
