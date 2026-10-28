> ⚠️ **DEPRECATED & ARCHIVED — DO NOT USE IN PRODUCTION**  
> This repository is **DEPRECATED and NOT USED IN PRODUCTION**. It has been completely superseded by **[Galaxyfun](https://github.com/SlimefunNewHorizons/Galaxyfun)** (StarSuites Suite 6). Kept strictly for historical reference and passive maintenance.

<div align="center">

  <img src="https://raw.githubusercontent.com/SlimefunNewHorizons/Galactifun2-drake/1.21-latin/banner.svg" alt="Galactifun2-drake Banner" width="920" />

# 🧪 Galactifun2-Drake

**Slimefun4 Addon with Native Rust Acceleration (Java 21 Project Panama FFM API)**

<p>
  <a href="https://github.com/SlimefunNewHorizons/Galactifun2-drake"><img src="https://img.shields.io/badge/GitHub-Galactifun2--Drake-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Java-21_FFM_Panama-F89820?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 21 FFM"/>
  <img src="https://img.shields.io/badge/Rust-FFM_Accelerated-FF4500?style=for-the-badge&logo=rust&logoColor=white" alt="Rust Native"/>
  <img src="https://img.shields.io/badge/Paper-1.21.11-38BDF8?style=for-the-badge&logo=minecraft&logoColor=white" alt="Paper 1.21.11"/>
</p>

</div>

> ### 🏰 Join the Official DrakesCraft Community!
> 
> * 🎮 **Server IP**: `mc.drakescraft.cl` *(Java 1.21.11 & Bedrock)*
> * 💬 **Official Discord**: [discord.gg/drakescraft](https://discord.gg/rv3vtXZTk7)
> * 🌐 **Web & Guide**: [web.drakescraft.cl](https://web.drakescraft.cl) — 🛒 **Store**: [web.drakescraft.cl/store](https://web.drakescraft.cl/store.html)
> 
> *Play with this addon and 80+ more optimized expansions live on our technical survival network!*

---

---

## ⚡ Zero-Risk Hybrid Model Highlights

`Galactifun2-Drake` integrates the Panama FFM component **`RustNativeBridge`** to delegate machine ticker acceleration and heavy calculations directly to the native `Slimefun-Rust` (`slimefun_ffi`):
- 🚀 **Nanosecond Tick Processing**: True parallel multithreading on CPU with no Garbage Collector pauses.
- 🛡️ **Full Preservation, No Reset (SQLite 0-Reset)**: Keeps all existing blocks and inventories in `stored-blocks.db` intact.

---

## 🛠️ Build

```bash
./gradlew build
```

Dependencies are resolved from the Drake Maven repository, <https://maven.drakescraft.cl> (GitHub Pages of
[`SlimefunNewHorizons/maven-repo`](https://github.com/SlimefunNewHorizons/maven-repo)):

| Line | Core | Java |
|---|---|---|
| 1.21.11 (production) | `slimefun-core 11.0-Drake-1.21.11-SNAPSHOT` | 21 |
| Universal 26.x (Paper 26.2) | `slimefun-core 11.0-Universal-26.x-SNAPSHOT` + `dough-core 1.3.1-Universal-26.x-SNAPSHOT` | 25 |

---

<div align="center">

**DrakesCraft Labs** · Maintained by [**JackStar6677-1**](https://github.com/JackStar6677-1)

</div>

---

## 📄 License & Upstream Attribution

This project is a sovereign fork maintained by [**JackStar6677-1**](https://github.com/JackStar6677-1) under [**DrakesCraft Labs**](https://github.com/SlimefunNewHorizons).

- **Original Project:** Created by the upstream authors and the open-source community.
- **DrakesCraft Optimizations:** Modernized for Paper/Purpur 1.21.11+, Java 21, high concurrency, asynchronous safety, and exploit/duplication prevention.
- **License:** Distributed under the original **GNU General Public License v3.0 (GPLv3)** (or original upstream license). See the [LICENSE](LICENSE) file for complete terms.
