# Japa Tools — Roblox Studio

> Production plugin by Gustavo **(Japa) Franco** for Roblox Studio: copy appearance and properties between Parts in seconds.

In version `0.1.0`, the core feature is **Appearance Copier** — set a reference Part, choose what to copy, and batch-apply it to selected Parts. Great for standardizing materials, colors, physics, and pivots without opening Properties a hundred times.

**Version:** `0.1.0` · **File:** `JapaTools_0.1.0.rbxmx` · **Toolbar:** `JapaTools`

---

## Why use it

- Standardize the look of dozens of Parts at once  
- Replicate Material / Color / Transparency without manual mistakes  
- Copy Size, Position, Orientation, and Origin (PivotOffset)  
- Batch-edit CanCollide, Anchored, and Massless  
- Optionally rename and copy children (SurfaceAppearance, Textures, etc.)

---

## Installation

1. Download `JapaTools_0.1.0.rbxmx` from this repository.
2. In Roblox Studio, go to **Plugins → Plugins Folder** (or drop the `.rbxmx` into your plugins folder).
3. Restart Studio (or reload plugins).
4. In the toolbar, click **JapaTools** to open the floating panel.

> The widget starts closed. Use the toolbar button whenever you want to open it again.

---

## Appearance Copier — how to use

1. Select the **reference** Part.
2. Click **Set Selection as Reference**.
3. Check the properties you want to copy (Select All is available per group).
4. (Optional) Set a **Custom Name** and/or enable **Copy Children**.
5. Select the target Parts.
6. Click **Apply to Selected Parts**.
7. Use **Clear Reference** when you are done.

The plugin uses **ChangeHistoryService**, so changes are undoable in Studio.

### Available properties

**Appearance**
- Color · DoubleSided · Material · MaterialVariant  
- Reflectance · RenderFidelity · Transparency  

**Transform**
- Size · Position · Orientation  
- Origin Position · Origin Orientation (`PivotOffset`)  

**Physics / behavior**
- CanCollide · Anchored · Massless  

**Extras**
- **Custom Name** — applies a custom name to target Parts  
- **Copy Children** — copies dependencies such as SurfaceAppearance, Textures, etc.

Reference values appear next to each checkbox so you can review them before applying.

---

## Interface

- Dockable panel with **collapsible** sections
- Visual feedback for reference, found dependencies, and common errors
- **Future Tools (Coming Soon)** section reserved for upcoming features

---

## Repository contents

```
JapaTools_RobloxStudio/
└── JapaTools_0.1.0.rbxmx   # ready-to-install Studio plugin
```

---

## Roadmap

More production tools are planned for the same modular UI. Suggestions and bug reports are welcome.

---

## Author

**Gustavo Franco** · AKA **Japa** · 2025  

Built to save production time in Studio. If it helps you (or something breaks), reach out.

Sister repo: [JapaTools_Blender](https://github.com/japabrandao3d/JapaTools_Blender)
