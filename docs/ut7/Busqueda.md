# Búsqueda de documentación técnica

La documentación técnica permite **instalar, configurar, comprender y solucionar problemas** de hardware y software.

## Fuentes habituales
| Fuente | Ventaja | Precaución |
|---|---|---|
| Buscador web | Encuentra información rápidamente | Comprobar fecha y autor |
| Manual oficial | Información de primera mano | Elegir versión correcta |
| Foro técnico | Problemas y soluciones reales | Las respuestas pueden quedar obsoletas |
| IA | Explicaciones y propuestas | Verificar todo lo importante |

## Búsquedas más precisas
- Comillas: buscar una **frase exacta**.
- `site:` limitar a un dominio.
- `filetype:pdf` buscar documentación PDF.
- Incluir **nombre del programa, versión, error y sistema operativo**.

```text
"permission denied" site:docs.github.com
filetype:pdf manual placa base
```

## Métodos útiles para programadores
- Consultar documentación oficial y notas de versión.
- Leer la ayuda integrada (`--help`, `man` en sistemas Unix).
- Usar foros como Stack Overflow, comprobando fechas y contexto.
- Reproducir el problema y probar la solución de forma segura.

```bash
man git
git --help
```

> [!TIP]
> Cuando uses IA, contrasta comandos, librerías y soluciones con documentación oficial antes de aplicarlos.

**Repaso:** ¿Por qué indicar la versión de un programa en una búsqueda? **Porque algunas instrucciones cambian entre versiones.**
