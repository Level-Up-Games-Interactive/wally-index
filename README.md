# Level Up Games – Private Wally Registry Index

This repository is the **private Wally package index** for **Level Up Games**.

It is used internally to host, version, and distribute Roblox packages across Level Up Games projects using the **Wally** package manager.

---

## 🔒 Private Repository

This repository is **not intended for public use**.

- Package metadata is managed internally
- Access is restricted to authorized contributors
- Publishing requires a valid API key
- Package contents are served through a private registry backend

If you do not have explicit access, this registry is not usable.

---

## 📦 What This Repository Is

This repository contains:
- Package metadata (package names, scopes, and versions)
- Registry configuration (`config.json`)
- Index data consumed by the Wally CLI

This repository **does not store package source code**.  
Actual package archives are stored and served by the Level Up Games private Wally backend.

---

## ⚙️ How It’s Used

Internal projects reference this registry in their `wally.toml`:

```toml
registry = "https://github.com/Level-Up-Games-Interactive/wally-index"
