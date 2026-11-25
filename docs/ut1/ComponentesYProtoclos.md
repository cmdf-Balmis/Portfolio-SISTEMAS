# Componentes y protocolos de red

## Componentes de una red
| Componente | Función |
|---|---|
| Switch | Conecta equipos de una LAN y utiliza direcciones MAC |
| Router | Interconecta redes y dirige tráfico con direcciones IP |
| Hub | Repite señales a todos sus puertos |
| Bridge | Conecta segmentos de red y filtra tráfico |
| Patch panel | Organiza el cableado físico |
| Servidor | Ofrece servicios y recursos |
| Cliente | Solicita servicios al servidor |

Los medios de transmisión incluyen **par trenzado**, **fibra óptica** y enlaces **inalámbricos**.

## Protocolos comunes
| Protocolo | Uso |
|---|---|
| IP | Direccionamiento y encaminamiento |
| TCP | Comunicación fiable y orientada a conexión |
| UDP | Comunicación sin conexión, con menos sobrecarga |
| HTTP/HTTPS | Acceso a páginas web |
| DNS | Traduce nombres de dominio a direcciones IP |
| ICMP | Mensajes de diagnóstico de red |
| FTP | Transferencia de archivos |
| SMTP | Envío de correo |

## Mapas de red
- **Mapa físico:** equipos, puertos, cables y ubicación.
- **Mapa lógico:** direcciones IP, subredes, rutas y relaciones entre redes.

```bash
# macOS: comprobar conectividad
ping -c 4 example.com
```

> [!TIP]
> Recuerda la diferencia: el **switch** conecta dentro de una red; el **router** comunica redes diferentes.

**Repaso:** ¿Qué servicio relaciona un nombre web con una IP? **DNS.**
