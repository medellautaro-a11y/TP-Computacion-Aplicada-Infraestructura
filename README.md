# TP Computación Aplicada – Infraestructura

Trabajo Práctico Integrador de la materia Computación Aplicada.

## Integrantes
- LAUTARO MEDEL
- GASPAR MARI
- CHRISTELLE OLIVIA JADOUL
- JONATHAN JAVIER DELGADO MELGAREJO

## Descripción
Implementación de una infraestructura sobre Debian GNU/Linux que incluye:
- Servidor web Apache con PHP
- Base de datos MySQL
- Gestión de almacenamiento con múltiples discos
- Backups automáticos mediante scripts y cron
- Acceso remoto seguro por SSH con claves

## Estructura del repositorio

Cada directorio solicitado fue comprimido individualmente en formato `.tar.gz`:

- `root.tar.gz` → Configuración y archivos del usuario root
- `etc.tar.gz` → Archivos de configuración del sistema
- `opt.tar.gz` → Scripts y utilidades (backup)
- `www_dir.tar.gz` → Sitio web (index.php, logo.png)
- `backup_dir.tar.gz` → Backups generados automáticamente

Además se incluye:
- Diagrama topológico de la infraestructura
- Scripts de backup y automatización

## Tecnologías utilizadas
- Debian GNU/Linux
- Apache 2
- PHP 7.4
- MySQL
- Cron
- Bash
- VirtualBox

## Observaciones
El sistema fue configurado para que los discos y servicios se monten y levanten automáticamente al iniciar el sistema.
