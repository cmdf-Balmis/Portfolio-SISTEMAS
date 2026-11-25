# Introducción al hardware

## ¿Qué es la informática?
La **informática** estudia el tratamiento automático de la información. Un sistema informático combina **hardware** (partes físicas), **software** (programas), personas y documentación.

## Representación de la información
El procesador interpreta instrucciones en binario, utilizando **0** y **1**. Los sistemas de numeración habituales son:

| Sistema | Base | Símbolos |
|---|---:|---|
| Binario | 2 | 0 y 1 |
| Octal | 8 | 0 a 7 |
| Decimal | 10 | 0 a 9 |
| Hexadecimal | 16 | 0 a 9 y A a F |

## Conversión entre bases
- **Binario → decimal:** sumar las potencias de 2 cuyos bits valgan 1. `10110₂ = 16 + 4 + 2 = 22₁₀`.
- **Decimal → binario:** dividir entre 2 repetidamente y leer los restos desde el último.
- **Binario → octal:** agrupar de **3 en 3** desde la derecha.
- **Binario → hexadecimal:** agrupar de **4 en 4** desde la derecha.
- **Hexadecimal → decimal:** cada cifra se multiplica por la potencia de 16 correspondiente.

```text
46 ÷ 2 = 23 resto 0
23 ÷ 2 = 11 resto 1
11 ÷ 2 =  5 resto 1
 5 ÷ 2 =  2 resto 1
 2 ÷ 2 =  1 resto 0
 1 ÷ 2 =  0 resto 1
Resultado: 101110₂
```

> [!TIP]
> Para pasar de binario a decimal recuerda las potencias: 1, 2, 4, 8, 16, 32, 64, 128, 256.

**Repaso:** ¿Cuánto vale `11001₂` en decimal? **25**.
