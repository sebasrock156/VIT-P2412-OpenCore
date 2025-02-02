# VIT P2412 OpenCore Hackintosh

[![EFIAcer OSX](https://img.shields.io/badge/EFIAcerHackintosh-available_here-violet.svg)](https://github.com/sebasrock156/Acer-E5-572-TMP246-OpenCore)
[![AMD OSX](https://img.shields.io/badge/AMDOSX-alpha_available-violet.svg)](https://github.com/sebasrock156/Asus-X555QA-Hackintosh)
[![Huawei OSX](https://img.shields.io/badge/HuaweiHackintosh-available-violet.svg)](https://github.com/sebasrock156/Huawei-Matebook-D14-21-OpenCore)

Esto hace parte del proyecto Hackintosh con OpenCore, por primera vez (creo) para una VIT (la computadora bolivariana).

**Más información sobre MacOS Monterey:**

[![MacOS Monterey](https://i.imgur.com/G3qQ9T2.png)](https://github.com/sebasrock156/Acer-Aspire-5749-Hackintosh/tree/Monterey)

**Estado:** 👨🏾‍🏭 Finalizado (pruebe con este [EFI de lanzamiento](https://github.com/sebasrock156/VIT-P2412-OpenCore/releases) )💻

**To do:** Solucionar salida de imagen por VGA.


Hardware | Model
--- |:--:
![motherboard](https://i.imgur.com/kjUKjB2.png) | Intel HM86 (Haswell)
![processor](https://i.imgur.com/wpQP7WW.png) | Intel Core i3 (4ta Generación) 4100M 2 Núcleos/4 Hilos@2,5Ghz
![igpu](https://i.imgur.com/pk2H9Aw.png) | Intel HD Graphics 4600 512MB VRAM@400Mhz
![audio](https://i.imgur.com/A7RRuUn.png) | ALC269 (integrada)
![wlan](https://i.imgur.com/9eDLwo9.png) | Realtek RTL8723BE (sin soporte)
Ethernet | Realtek 8111
![ddr3](https://i.imgur.com/5MAnSyf.png) | Samsung 6GB(1x2+1x4) DDR3@1600Mhz
![ssd](https://i.imgur.com/pozDx4X.png) | Crucial BX500 SSD 240GB (Controlador 2258XT de SMI)
---


### Works:
---
<details>

- Opencore 0.9.2 ✅ (Although OC Menu doesn't recognize periphericals)

- Installer Boot ✅ (Installation on SSD: ~30/35 minutes)

- System Boot ✅

- USB Ports ✅

- VoodooPS2Controller/Keyboard+Touchpad ✅

- Camera ✅ (works perfectly)

- Battery charging and stats ✅

- Screen ✅ (1336x768)

- Audio Card ✅ (Could be sounds cutted)

- Wi-Fi ✅ (It's fully working)

 
</details>


### Not works:
---

<details>

- HDMI ❌ (Enable it with OCLP, but not for now)
- VGA/Displayport ❌ (System try put in 90Hz and the built-in screen crash)
