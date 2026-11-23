# XP Coordinación: descargas

Aquí se baja la app de escritorio de XP Coordinación. Para entrar hace falta la cuenta de Discord de la escuela.

**[Bajar la última versión](https://github.com/leosanxyz/xp-descargas/releases/latest)**

| Tu equipo | Archivo |
| --- | --- |
| Windows 10 o 11 | `XP-…-windows-x86_64.exe` |
| macOS 13 o más nuevo (Apple o Intel) | `XP-…-mac.dmg` |
| Linux (Ubuntu 22.04 o más nuevo, Debian 12, Fedora, Mint, Arch) | `XP-…-x86_64.AppImage` |

La app se actualiza sola: cuando hay una versión nueva, avisa y se instala al reiniciarla.

Todavía no tiene firma de Apple ni certificado de Windows, así que el sistema avisa la primera vez. Es esperado.

## Windows

1. Abre el `.exe`. No pide permisos de administrador.
2. Si el navegador dice que el archivo «no se descarga normalmente», elige **Conservar**.
3. En la ventana azul **«Windows protegió tu PC»**, pulsa **Más información** y luego **Ejecutar de todas formas**.
4. Sigue el asistente. Queda «XP Coordinación» en el menú Inicio.

## macOS

1. Abre el `.dmg` y arrastra **XP Coordinación** a **Aplicaciones**.
2. Ábrela. Sale **«No se abrió "XP Coordinación"»**: pulsa **Listo**, no «Trasladar a la papelera».
3. Abre **Ajustes del Sistema › Privacidad y seguridad**, baja hasta el mensaje de XP Coordinación y pulsa **Abrir igualmente**.
4. Desde ahí abre con doble clic, como cualquier app.

## Linux

```sh
mkdir -p ~/Aplicaciones
mv ~/Descargas/XP-*-x86_64.AppImage ~/Aplicaciones/XP-Coordinacion.AppImage
chmod +x ~/Aplicaciones/XP-Coordinacion.AppImage
~/Aplicaciones/XP-Coordinacion.AppImage
```
