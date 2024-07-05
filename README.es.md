# README.md
- [Deutsch](README.de.md)
- [English](README.md)
- [Spanish](README.es.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)

# iCroc - Aplicación CLI de Croc para iOS y macOS

Descargar [la última versión desde la App Store](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Rediseño completo de toda la interfaz de la aplicación y la lógica de operación.
- Actualización de la versión incrustada de croc a v10.0.8.
- Añadir soporte para la función Handoff de iOS y macOS.
- Soporte para más idiomas.

V1.1
---
- Rediseño del icono de la aplicación.
- Corrección de errores y mejoras de rendimiento.

V1.0
---
croc es una herramienta que permite a dos computadoras transferir archivos y carpetas de manera simple y segura. Hasta donde sé, croc es la única herramienta CLI de transferencia de archivos que hace todo lo siguiente:

- Permite la transferencia de datos entre dos computadoras (usando un relé).
- Proporciona cifrado de extremo a extremo (usando PAKE).
- Facilita transferencias multiplataforma (Windows, Linux, Mac).
- Permite transferencias de múltiples archivos.
- Permite reanudar transferencias interrumpidas.
- No requiere servidor local ni reenvío de puertos.
- Prioriza IPv6 con respaldo en IPv4.
- Puede usar proxy, como tor.

La aplicación de línea de comandos en la que se basa se puede encontrar aquí:

https://github.com/schollz/croc

## Activar iCroc en Configuración de macOS
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Enviar archivos rápidamente con iCroc
- Selecciona archivos en Finder y luego usa abrir con iCroc.
- En Finder selecciona archivos y usa ⌘+C para copiar, luego abre iCroc y usa ⌘+V para enviar archivos.
- Arrastra archivos a iCroc.

# ⚡ Handoff
- Instala la aplicación iCroc en dispositivos iOS y macOS.
- Habilita la función Handoff en iOS y macOS.
- Cuando el remitente genera una frase de código, iCroc en el otro dispositivo recibirá automáticamente la frase de código.

# 🔮 Reanudar tarea interrumpida
- El remitente vuelve a enviar el archivo y el receptor usa el formato nueva frase de código@frase de código antigua, ej: 4161-mambo-young-baby@7611-south-concept-satire.
- El remitente vuelve a enviar el archivo utilizando el token personalizado como la frase de código anterior.

# 💾 Carpeta de recepción personalizada
- La carpeta de recepción se guardará en ~/Downloads/'${code-phrase}'.
- Usar '@folderName' guardará en ~/Downloads/folderName, ej: 8443-siren-mayor-origin@mypics.
- Usar la misma carpeta de destino reanudará automáticamente las tareas de transferencia interrumpidas.