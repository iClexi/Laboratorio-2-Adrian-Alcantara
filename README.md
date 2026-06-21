<div align="center">

# Laboratorio 2 - Paquetes, Tareas Programadas y Discos

### Practicas de administracion Linux con APT, cron, at, particiones y montaje de almacenamiento.

![Platform](https://img.shields.io/badge/Platform-Ubuntu%20Server-E95420?logo=ubuntu&logoColor=white)
![Package](https://img.shields.io/badge/Packages-APT-blue)
![Automation](https://img.shields.io/badge/Automation-Cron%20%7C%20At-green)
![Storage](https://img.shields.io/badge/Storage-EXT4%20%7C%20Mount-orange)
![Topic](https://img.shields.io/badge/Topic-Linux%20Administration-purple)

</div>

---

## Descripcion

Este repositorio documenta tres practicas de administracion en Ubuntu Server. El laboratorio cubre gestion de paquetes, programacion de tareas y configuracion basica de discos, particiones y sistemas de archivos.

## Practicas incluidas

| Practica | Tema | Herramientas |
| --- | --- | --- |
| Practica 1 | Gestion de paquetes | `apt`, `apt-cache`, repositorios |
| Practica 2 | Tareas programadas | `cron`, `crontab`, `at` |
| Practica 3 | Discos y particiones | `lsblk`, `fdisk`, `mkfs.ext4`, `mount` |

## How-To: ejecutar las practicas

1. Usa una VM Ubuntu Server de laboratorio.
2. Entra con un usuario con permisos administrativos.
3. Abre cada archivo de practica en orden.
4. Ejecuta los comandos paso a paso.
5. Verifica cada resultado antes de pasar a la siguiente seccion.

## Requisitos

- Ubuntu Server.
- Acceso `sudo`.
- Un disco secundario de prueba para la practica de particiones.
- Paquetes `at` y herramientas basicas del sistema.

## Comandos clave

```bash
sudo apt update
sudo apt upgrade
apt-cache search bashtop
crontab -e
at now + 2 minutes
lsblk
sudo fdisk /dev/sdb
sudo mkfs.ext4 /dev/sdb1
sudo mount /dev/sdb1 /mnt
```

## Estructura del repositorio

```text
Laboratorio-2-Adrian-Alcantara/
├── Practica 1 Laboratorio 2
├── Practica 2 Laboratorio 2
├── Practica 3 Laboratorio 2
└── README.md
```

## Resultado esperado

Al finalizar, el estudiante debe poder instalar y eliminar paquetes, automatizar tareas con cron/at y preparar almacenamiento adicional en Linux usando particiones y formato EXT4.
