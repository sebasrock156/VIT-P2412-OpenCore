# VIT P2412 OpenCore Hackintosh

>**DESCARGO DE RESPONSABILDAD**: No poseo autorización de Venezolana de Industria Tecnológica C.A. o de Apple Inc. para la modificación, uso o distribución de sus dispositivos/sistemas operativos fuera del territorio de la República Bolivariana de Venezuela; este EFI para OpenCore fue desarrollado en base a la petición de un cliente, cualquier responsabilidad legal, judicial o de uso legítimo debe ser solicitado/ejercido por sus verdaderos autores.
>
>
----

Esto hace parte del proyecto Hackintosh con OpenCore, por primera vez (creo) para una VIT (la computadora bolivariana).


**Más información sobre MacOS Monterey:**

[![MacOS Monterey](https://i.imgur.com/uNFD2qc.png)](https://github.com/sebasrock156/VIT-P2412-OpenCore/tree/Monterey)

**Estado:** 👨🏾‍🏭 Finalizado (pruebe con este [EFI de lanzamiento](https://github.com/sebasrock156/VIT-P2412-OpenCore/releases) )💻

**To do:** Solucionar salida de imagen por VGA.


Hardware | Modelo
--- |:--:
![motherboard](https://i.imgur.com/kjUKjB2.png) | Intel HM86 (Haswell)
![processor](https://i.imgur.com/BzXF1mf.png) | Intel Core i5 (4ta Generación) 4200M 2 Núcleos/4 Hilos@2,5Ghz
![igpu](https://i.imgur.com/pk2H9Aw.png) | Intel HD Graphics 4600 512MB VRAM@400Mhz
![audio](https://i.imgur.com/A7RRuUn.png) | ALC269 (integrada)
![wlan](https://i.imgur.com/dUwPhAC.png) | Realtek RTL8723BE+Bluetooth 4.0 (sin soporte)
Ethernet | Realtek RTL8111
![ddr3](https://i.imgur.com/5MAnSyf.png) | Samsung 6GB(1x2+1x4) DDR3@1600Mhz
![ssd](https://i.imgur.com/Jixm0UG.png) | Crucial BX500 SSD 240GB (Celdas NAND TLC con controlador 2258XT de SMI)
---


### Funciona:
---
<details>

- Bootloader de OpenCore ✅

- Arranque de instalador ✅ (Con un SSD puede tardar cerca de 45 minutos)

- Arranque del sistema ✅

- Puertos USB ✅

- Teclado+Touchpad ✅

- Cámara ✅

- Carga de batería y estadísticas ✅

- Pantalla ✅ (1336x768)

- Tarjeta de audio ✅ (sólo con el códed 23)

- HDMI ✅

- Lector de tarjetas SD  ✅
 
</details>


### No funciona:
---

<details>

- Wi-Fi/Bluetooth ❌ (Las tarjetas de Realtek son completamente incompatibles, cámbiela por una de Intel)

- VGA/Displayport ❌ (Quiero pensar que es por un error de configuración de la tarjeta gráfica o porque el framebuffer de estos procesadores es muy débil)
