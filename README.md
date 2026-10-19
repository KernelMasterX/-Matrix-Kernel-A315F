# 🟢 Matrixx Kernel for Samsung Galaxy A31 (SM-A315F)

Custom Linux 4.14 kernel built for the **Samsung Galaxy A31** (MediaTek Helio P65), featuring native **KernelSU Next** integration and optimized for stability and performance.

---

## ✨ Features
* **KernelSU Next**: Integrated out-of-the-box for advanced, secure root management.
* **Base Architecture**: Linux Kernel 4.14 (tailored for `a31_defconfig`).
* **Toolchain**: Compiled using optimized prebuilt toolchains.
* **AnyKernel3**: Packaged as a universal flashable zip, compatible with TWRP and OrangeFox custom recoveries.

---

## 📱 Compatibility
* **Device**: Samsung Galaxy A31 (`SM-A315F`)
* **Chipset**: MediaTek Helio P65
* **OS / ROMs**: Compatible with One UI and Treble-based custom GSI ROMs.

---

## 📥 Downloads & Installation
1. Head over to the **[Releases](../../releases)** tab.
2. Download the `Matrix-Kernel-A31-AnyKernel3.zip` file.
3. Boot your device into a Custom Recovery (TWRP / OrangeFox).
4. Flash the zip file.
5. Wipe Dalvik/Cache (optional, recommended) and reboot.

---

## 🛠️ Build from Source (GitHub Actions)
This project is configured to build automatically via GitHub Actions (`ubuntu-22.04`). 
* Toolchain setup, KernelSU Next patching, and AnyKernel3 packaging are fully automated in `.github/workflows/build-kernel.yml`.

---

##  🙏 Credits & Acknowledgements
* **[Physwizz](https://github.com/physwizz)** & upstream maintainers for base device trees, kernel sources, and continuous inspiration.
* **[KernelSU Next](https://github.com/rifsxd/KernelSU-Next)** team for the amazing root solution.
* **[osm0sis](https://github.com/osm0sis)** for AnyKernel3 and Android Image Kitchen (AIK).
---

## ⚠️ Disclaimer
> *Your warranty is now void. I am not responsible for bricked devices, dead storage, or data loss. Flash at your own risk!*
