# Ejercicio 1 — Ubuntu en Windows (WSL)

## Objetivo
Instalar y comprobar el funcionamiento de Ubuntu en Windows utilizando Windows Subsystem for Linux (WSL).

## Captura 1 — Comprobación desde Windows PowerShell

Comando ejecutado:

```powershell
wsl -d Ubuntu -- lsb_release -a
```

Resultado:

```text
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 26.04.1 LTS
Release:        26.04
Codename:       resolute
```

![Captura de Ubuntu desde PowerShell](capturas/ejercicio1-powershell.png)

## Captura 2 — Terminal de Ubuntu en WSL

Comando ejecutado:

```bash
pwd
```

Resultado:

```text
/home/asus
```

![Captura de la terminal Ubuntu en WSL](capturas/ejercicio1-ubuntu.png)

## Conclusión
Se ha instalado Ubuntu 26.04.1 LTS mediante WSL. Los comandos ejecutados desde PowerShell y desde Ubuntu confirman que el entorno funciona correctamente.

> **Pendiente:** subir los dos archivos PNG a la carpeta `capturas/` con los nombres indicados para que se muestren las imágenes aquí.
