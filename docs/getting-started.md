# Get Started

Welcome to the **Cofy Dev Unity Template**! This guide will help you quickly set up the project using the official GitHub template.

---

## 🧰 Prerequisites

Make sure you have the following installed:

- **Unity 2022.3.6f1** or a later version

---

## 🚀 Clone the Project

To get started, clone the template repository:

```bash
git clone --recurse-submodules https://github.com/felixwongong/cfUnityTemplate.git
```

> 💡 This automatically fetches all submodules.

If you already cloned the repository without submodules, run the following:

```bash
git submodule update --init --recursive
```

---

## 📦 Included Submodules

The template includes the following libraries as Git submodules:

- [`cfEngine`](https://github.com/felixwongong/cfEngine) — Core utility and logic layer
- [`cfUnityEngine`](https://github.com/felixwongong/cfUnityEngine) — Unity-specific components and extensions

These are located under:

```text
Assets/Modules/
├── cfEngine/
└── cfUnityEngine/
```

You're now ready to open the project in Unity and start developing!
