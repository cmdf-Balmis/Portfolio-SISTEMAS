# Placa base (motherboard)

La **placa base** es el circuito impreso que conecta y permite comunicarse a los componentes del ordenador.

## Elementos principales
| Elemento | Función |
|---|---|
| Socket | Aloja el procesador |
| Ranuras DIMM | Instalan la memoria RAM |
| Chipset | Gestiona varias comunicaciones y puertos |
| PCI Express (PCIe) | Tarjetas gráficas, red y SSD compatibles |
| Conectores SATA | Discos y unidades ópticas |
| ATX/EPS | Alimentación de placa y procesador |
| Puertos traseros | USB, red, audio, vídeo, etc. |

## Formatos físicos
**ATX**, **microATX** y **Mini-ITX** indican dimensiones y disposición. El formato debe encajar en la caja.

## Socket LGA y PGA
- **LGA:** pines en el zócalo de la placa base.
- **PGA:** pines en la CPU.

## BIOS y UEFI
Son firmware que inicializan componentes y gestionan el arranque. **UEFI** ofrece características modernas como arranque desde GPT y Secure Boot.

```text
Compatibilidad: CPU ↔ socket ↔ placa base ↔ RAM ↔ caja
```

> [!WARNING]
> Aunque dos procesadores sean de la misma marca, no necesariamente utilizan el mismo socket.

**Repaso:** ¿Dónde se conecta una GPU dedicada? **Normalmente en PCIe x16.**
