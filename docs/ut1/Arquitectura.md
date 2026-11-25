# Arquitectura de computadores

## Von Neumann
La arquitectura de **Von Neumann** utiliza una memoria compartida para **datos e instrucciones**. Es la base conceptual de muchos ordenadores.

| Componente | Función |
|---|---|
| CPU | Ejecuta instrucciones |
| Unidad de control | Interpreta y coordina operaciones |
| ALU | Realiza operaciones aritméticas y lógicas |
| Memoria | Guarda datos e instrucciones |
| Entrada/salida | Comunicación con el exterior |

## Los tres buses
- **Datos:** transporta valores.
- **Direcciones:** indica la posición o dispositivo al que acceder.
- **Control:** señales de lectura, escritura, interrupción y sincronización.

## Ciclo de instrucción
```text
Fetch (buscar) → Decode (decodificar) → Execute (ejecutar)
```

El **contador de programa (PC)** guarda la dirección de la siguiente instrucción.

## Comparación de arquitecturas

| Arquitectura | Datos e instrucciones |
|---|---|
| Von Neumann | Comparten memoria y vías de acceso |
| Harvard | Memorias y buses separados |
| Harvard modificada | Combina separación interna y flexibilidad |

> [!NOTE]
> El «cuello de botella de Von Neumann» se produce cuando el acceso compartido a memoria limita el rendimiento.

**Repaso:** ¿Qué bus indica una ubicación de memoria? **El bus de direcciones.**
