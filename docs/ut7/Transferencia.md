# Transferencia de ficheros

La transferencia de archivos permite **subir, descargar o compartir** información entre equipos, servidores y servicios.

## Protocolos y herramientas
| Tecnología | Función | Seguridad |
|---|---|---|
| FTP | Transferir archivos | Normalmente sin cifrado |
| SFTP | Transferir archivos mediante SSH | Comunicación cifrada |
| FTPS | FTP protegido mediante TLS | Comunicación cifrada |
| FileZilla | Cliente gráfico de transferencias | Según protocolo y configuración |

**SFTP y FTPS son tecnologías distintas**, aunque ambas pueden proteger las transferencias.

## Otras formas de compartir
- **Nube:** Google Drive, OneDrive, Dropbox; archivos accesibles según permisos y conexión.
- **Carpetas compartidas en LAN:** recursos accesibles entre equipos de una misma red, habitualmente con SMB.
- **Disco externo:** transporte físico de archivos.

## Ejemplo con un cliente SFTP
```bash
# Ejemplo genérico de conexión (requiere cuenta y servidor)
sftp usuario@servidor.ejemplo.test
```

> [!WARNING]
> Comprueba permisos y destinatarios al compartir información sensible; no uses FTP sin protección en redes no confiables.

**Repaso:** ¿Qué programa permite gestionar visualmente una transferencia por SFTP? **FileZilla.**
