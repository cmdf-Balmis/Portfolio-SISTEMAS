# Memoria RAM

La **RAM** almacena temporalmente datos e instrucciones que utilizan los programas. Es **volátil**: pierde su contenido al apagar el equipo.

## DRAM y SRAM
| Tipo | Características | Uso frecuente |
|---|---|---|
| DRAM | Necesita refresco; más económica por bit | Memoria principal |
| SRAM | Más rápida y cara; no necesita refresco | Caché de CPU |

## Generaciones y formatos
- **DDR3, DDR4, DDR5:** generaciones con características y conectores diferentes; no son intercambiables.
- **DIMM:** módulos habituales de sobremesa.
- **SO-DIMM:** módulos compactos, habituales de portátiles.
- **Dual channel:** permite usar dos canales de memoria y aumentar el ancho de banda cuando el equipo lo admite.

## Velocidad y latencia
La velocidad de transferencia de la RAM se expresa a menudo en **MT/s**, no debe confundirse con MHz. La latencia también influye en el rendimiento.

```text
DDR4-3200, canal de 64 bits (8 bytes):
3200 MT/s × 8 bytes = 25 600 MB/s = 25,6 GB/s
```

> [!TIP]
> Antes de comprar RAM revisa la compatibilidad con la placa base y el procesador.

**Repaso:** ¿Qué ocurre con la RAM al apagar? **Pierde la información almacenada.**
