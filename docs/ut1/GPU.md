# GPU: unidad de procesamiento gráfico

La **GPU** acelera el tratamiento de imágenes, vídeo, gráficos 3D y algunas tareas de cálculo paralelo, como inteligencia artificial.

## GPU integrada y dedicada
| GPU integrada (iGPU) | GPU dedicada |
|---|---|
| Forma parte del procesador o chip | Tarjeta o chip gráfico independiente |
| Suele compartir RAM del sistema | Suele disponer de VRAM propia |
| Adecuada para tareas cotidianas | Adecuada para trabajos gráficos exigentes |

## Conceptos clave
- **Paralelismo:** muchas unidades realizan cálculos simultáneos.
- **VRAM:** almacena texturas, modelos y datos gráficos.
- **GDDR / HBM:** tecnologías de memoria gráfica.
- **Ray tracing:** técnica que simula efectos de la interacción de la luz.

```text
CPU: coordina tareas generales
GPU: acelera tareas paralelas y gráficas
```

> [!NOTE]
> Una GPU con más VRAM no es automáticamente más rápida: también importan arquitectura, potencia y ancho de banda.

**Repaso:** ¿Para qué sirve la VRAM? **Para almacenar los datos que necesita el procesamiento gráfico.**
