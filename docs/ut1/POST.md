# POST: comprobaciones del arranque

**POST** (*Power-On Self-Test*) es una secuencia de comprobaciones que inicia el firmware al encender el ordenador **antes de cargar el sistema operativo**.

## Fases principales
1. **Detectar** componentes como CPU, RAM, gráfica y almacenamiento.
2. **Verificar** que el hardware esencial responde.
3. **Informar** mediante mensajes, luces de diagnóstico o pitidos si aparece un fallo.
4. **Entregar el control** al cargador de arranque (*bootloader*), si es posible.

```text
Encender → BIOS/UEFI → POST → dispositivo de arranque
                             → bootloader → sistema operativo
```

## ¿Qué pasa si algo falla?
| Síntoma | Posible comprobación |
|---|---|
| No muestra imagen | Alimentación, RAM, CPU o gráfica |
| Emite pitidos | Consultar el manual del fabricante |
| «No boot device» | Revisar conexión y orden de arranque del disco |

> [!NOTE]
> Los pitidos no tienen significado universal: dependen del modelo de placa base y del firmware.

**Ejemplo de clase:** si el disco del sistema está desconectado, el equipo podría completar el POST pero no encontrar un dispositivo desde el que iniciar Windows o Linux.

**Repaso:** ¿Qué hace el POST? **Comprueba hardware antes de arrancar el sistema operativo.**
