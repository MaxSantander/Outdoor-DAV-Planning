# Instrucciones para clonar y trabajar con este repositorio

## 1. Clonar el repositorio desde GitHub

1. Abre una terminal (cmd.exe o PowerShell).
2. Ejecuta:

   git clone https://github.com/MaxSantander/Outdoor-DAV-Planning.git

3. Entra en la carpeta del proyecto:

   cd Outdoor-DAV-Planning

## 2. Configuración recomendada

- Asegúrate de tener instalado Git y, si quieres usar la CLI de GitHub, también la herramienta `gh`.
- Si trabajas en Windows y ves advertencias de "safe.directory", ejecuta:

   git config --global --add safe.directory <ruta_del_proyecto>

## 3. Subir cambios

1. Haz tus cambios y guarda los archivos.
2. Ejecuta:

   git add .
   git commit -m "Describe brevemente tus cambios"
   git push origin master

## 4. Crear un nuevo repositorio (opcional)

Si quieres crear un nuevo repositorio desde cero en otra máquina:

1. Inicializa git:

   git init

2. Añade los archivos y haz el primer commit:

   git add .
   git commit -m "Initial commit"

3. Crea el repositorio en GitHub (usando la web o la CLI `gh`).
4. Añade el remoto y sube los cambios:

   git remote add origin https://github.com/MaxSantander/<NUEVO_REPO>.git
   git push -u origin master

## 5. Autenticación con GitHub CLI (si usas `gh`)

Si es la primera vez que usas la CLI de GitHub:

   gh auth login

Sigue las instrucciones para autenticarte.

---

**¡Listo! Ahora puedes seguir trabajando en el proyecto desde cualquier computadora.**
