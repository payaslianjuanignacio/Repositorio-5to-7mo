# Documentación, Git y GitHub

## 1. Documentación

La documentación es la información escrita que explica cómo funciona un sistema, cómo fue desarrollado y cómo se utiliza. Permite que otras personas comprendan el proyecto y puedan continuarlo o mantenerlo.

## 2. Git

Git es un sistema de control de versiones. Registra los cambios realizados en los archivos de un proyecto y permite consultar o recuperar versiones anteriores. Se utiliza desde la computadora mediante comandos o herramientas gráficas.

## 3. GitHub

GitHub es una plataforma en línea que permite alojar repositorios Git, compartir proyectos y colaborar con otras personas. Ofrece herramientas para revisar cambios, proponer modificaciones y organizar el trabajo.

## 4. Diferencia entre Git y GitHub

- **Git:** herramienta que controla las versiones del proyecto.
- **GitHub:** servicio web que aloja repositorios Git y facilita compartir y colaborar.

Git puede utilizarse sin GitHub; GitHub utiliza Git para gestionar el historial de los repositorios.

## 5. Comandos básicos de Git

```bash
git init                 # inicia un repositorio local
git status               # muestra el estado de los archivos
git add .                # prepara los cambios
git commit -m "Primer cambio"  # guarda una versión
git push                 # envía los commits al repositorio remoto
git pull                 # incorpora cambios del repositorio remoto
```

Para usar `push` o `pull`, el repositorio local debe estar conectado a un repositorio remoto y configurado con los permisos correspondientes.

## 6. Ejemplo práctico

Un equipo desarrolla una aplicación. Cada integrante realiza cambios y los registra con Git. Luego comparte esos cambios en GitHub para que el resto del equipo pueda revisarlos e incorporarlos.

## Para recordar

Git registra el historial de cambios; GitHub permite alojar y compartir repositorios Git en internet.

## Temas relacionados

- [Documentación técnica y de usuario](../documentacion-tecnica-usuario/README.md)
- [Documentación de un proyecto](../documentacion-proyecto/README.md)
