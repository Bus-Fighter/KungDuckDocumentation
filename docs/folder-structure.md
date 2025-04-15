---
uid: project.folder-structure
title: 📁 Folder Structure
description: Overview of the recommended folder structure in the Cofy Dev Unity Template.
---

# 📁 Folder Structure

Here's a quick overview of the default folder layout used in the **Cofy Dev Unity Template**. This structure helps keep your project clean, scalable, and modular.

---

## `Assets/`

Root folder for most project content.

### └── `Art/`
🎨 Put all your art assets here — textures, sprites, models, etc.

---

### └── `Info/`
📊 Stores structured data files (like `.xlsx` or `.csv`).  
Each subfolder represents a specific data type — e.g., `DialogueInfo`, `InventoryInfo`.

> 💡 You can sync Info data directly from Google Drive using the [GDriveMirror Get Started](xref:tools.gdrivemirror-get-started) guide.

---

### └── `Modules/`
📦 Submodule folder for external/custom libraries — such as:

- `cfEngine`
- `cfUnityEngine`

This keeps your core systems modular and version-controlled.

---

### └── `Packages/`
📁 Contains NuGet or Unity package references.

You typically won't need to edit this manually — but it's useful for custom NuGet-based workflows.

---

### └── `Prefab/`
🏗️ Stores all prefabs used in the project.

> ⚠️ This project uses **Addressables**, so most prefabs don’t need to go into a `Resources/` folder.

---

### └── `Scripts/`
🧠 Holds your project-specific logic and gameplay scripts.

- Organized by feature or system.
- Uses **Assembly Definitions (`.asmdef`)**.
- You’ll need to reference packages like `cfEngine` inside your `.asmdef` files to use them.

---

## 🧭 Tips

- Keep folders modular and purpose-driven.
- Avoid mixing unrelated asset types.
- Use `.asmdef` to reduce compile time and maintain clean boundaries.

For more best practices, check out the [Project Setup](xref:project.setup) section.
