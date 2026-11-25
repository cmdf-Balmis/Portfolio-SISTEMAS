# Interfaces y conectores

Una **interfaz** permite conectar y comunicar componentes; puede ser física o lógica.

| Interfaz | Uso principal |
|---|---|
| SATA | HDD, SSD SATA, unidades ópticas |
| PCIe | GPU, SSD NVMe, tarjetas de expansión |
| M.2 | Formato frecuente de SSD compactos |
| USB | Teclados, memorias, discos, periféricos |
| HDMI / DisplayPort | Señal digital de vídeo y, habitualmente, audio |
| VGA | Vídeo analógico |
| Ethernet (RJ45) | Conexión de red por cable |
| Audio 3,5 mm | Auriculares y micrófonos analógicos |

## Detalles que suelen preguntar
- **USB-C es un tipo de conector**, no una velocidad concreta.
- **PCIe x1, x4, x8 y x16** indican número de carriles.
- **M.2 2280** indica 22 mm de ancho y 80 mm de largo.
- La velocidad efectiva depende de la versión, del dispositivo y de la configuración.

```text
SSD M.2 NVMe → PCI Express
SSD 2,5 pulgadas SATA → cable SATA de datos y energía
```

> [!TIP]
> No confundas «forma del conector» con «protocolo»: USB-C no equivale automáticamente a USB4.

**Repaso:** ¿Un SSD NVMe suele usar SATA? **No, normalmente PCIe.**
