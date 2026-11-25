# Procesador (CPU)

La **CPU** ejecuta instrucciones y coordina el procesamiento. Su rendimiento depende de varios factores, no solo de la frecuencia.

## Características importantes
- **Frecuencia (GHz):** ciclos de reloj por segundo.
- **IPC:** instrucciones completadas por ciclo, según la arquitectura.
- **Núcleos:** unidades de ejecución que permiten procesar trabajo en paralelo.
- **Hilos:** flujos de ejecución; tecnologías como SMT pueden exponer varios por núcleo.
- **Caché:** memoria muy rápida para información de uso frecuente.
- **ISA:** instrucciones y reglas que entiende un procesador, como x86-64 o ARM.
- **TDP (W):** referencia térmica para dimensionar la refrigeración, no necesariamente consumo máximo.

## Niveles de caché
| Nivel | Característica habitual |
|---|---|
| L1 | Muy pequeña y muy rápida |
| L2 | Intermedia |
| L3 | Más grande y generalmente compartida |

## Otros conceptos
Los procesadores híbridos pueden utilizar **P-Cores** (rendimiento) y **E-Cores** (eficiencia). **CISC** y **RISC** son enfoques de conjuntos de instrucciones. Algunas CPU integran una **GPU**.

```text
Rendimiento aproximado de un núcleo:
Instrucciones/s = ciclos/s × instrucciones/ciclo (IPC)
```

> [!TIP]
> Para elegir CPU comprueba socket, placa base, RAM compatible, alimentación y refrigeración.

**Repaso:** ¿Por qué una CPU de 3 GHz podría rendir más que una de 4 GHz? **Porque también importan el IPC y la arquitectura.**
