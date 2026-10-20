# Errores de instalación — Lumen & Fibra

## Registro de errores

| Error o mensaje | Causa | Solución aplicada | Fuente consultada |
|---|---|---|---|
| Al abrir Docker Desktop aparece: `WSL needs updating. Your version of Windows Subsystem for Linux (WSL) is too old.` | El Subsistema de Windows para Linux (WSL) estaba desactualizado, impidiendo que el motor de Docker arrancara correctamente. | Se abrió PowerShell como administrador y se ejecutó el comando `wsl --update`. Tras reiniciar el equipo, Docker Desktop arrancó sin problemas. | Documentación oficial de Microsoft y mensaje de aviso de Docker Desktop. |

## Comprobaciones previas
Para evitar otros errores típicos:
- Se comprobó que el puerto 8069 no estuviera ocupado por otro proceso antes de lanzar Odoo.
- Se verificó que la base de datos PostgreSQL arrancara correctamente antes de conectar Odoo.

## Uso de IA
Se utilizó una IA como apoyo únicamente para resolver dudas conceptuales sobre cómo solucionar el error de WSL y para revisar la sintaxis de los comandos de Docker en Windows, no para la redacción de esta documentación.