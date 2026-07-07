# isygold 👋

[![Sponsor](https://img.shields.io/badge/Sponsor-%24?logo=github&style=flat)](https://github.com/sponsors/isygold)

**Low-level graphics dev & vibecoder** — debugging, refactoring, and improving original DXVK code for Adreno GPUs on Android. I spot bottlenecks in Vulkan translation layers that is commonly seen or nobody else sees, and I stabilise or fix them (if possible).

---

## 🚀 Major Works

| Project | Description |
|---------|-------------|
| **[VEGAS DXVK](https://github.com/star-emu/vegas)** | Tier-aware DXVK fork with FSR 1.0 async upscale, motion-compensated frame gen, TBDR-adaptive draw-flush governor, bind-skip optimization, HAAE threshold tuning, and dynamic VRAM swap — purpose-built for Adreno 610/619/618/630/640/650/660/730 GPUs. |
| **[Star Engine DXVK](https://github.com/isygold/Star-Engine-DXVK-Releases)** | Stability-first DXVK v2.7.1 fork for Android emulators. Mid-frame command flushing, dynamic-state-aware bind-skip, and Android-native config paths. |
| **[VEGAS 2.4.1 Port](https://github.com/isygold/vegas-releases)** | Clean backport of select VEGAS features (FSR, frame gen, HAAE, bind-skip, governor) to vanilla DXVK 2.4.1 for maximum compatibility on older Turnip drivers. |
| **[DXVK Config Collection](https://github.com/isygold/DXVK.CONF-FILE-SETTINGS-)** | Curated game-specific `dxvk.conf` presets tuned for Adreno GPUs on Winlator/Star Emulator. |

---

## 🛠 What I Do

- **Debug & refactor** DXVK / Vulkan translation layers — identify GPU-specific bottlenecks on Qualcomm Adreno
- **Vibecode** optimizations into existing codebases (FSR compute pipelines, command buffer pacing, descriptor binding optimizations)
- **Port** upstream DXVK changes into VEGAS while keeping backward compatibility with GPLAsync/Turnip
- **Test** across multiple Adreno 610 and Android emulators (Winlator, Star Emulator)

---

## 📫 Reach Out

- Telegram: [t.me/isygold](https://t.me/isygold)
- Discord: `isygold`
- Open to collab on Vulkan/DXVK/Mesa internals — serious inquiries only

---
