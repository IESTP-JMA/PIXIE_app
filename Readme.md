# Pasos a seguir para la creación del repositorio grupal.

## 1. Crear la carpeta del proyecto :

   ```mkdir PIXIE.app```

## 2. Acceder a la carpeta del proyecto :

   ```cd PIXIE.app```

## 3. Inicializar repositorio :

   ```git init```

## 4. crear nuestro entorno virtual de python (al costado de venv ahi debe ir el nombre del entorno virtual).
   (si le pongo un .venv al costado de venv puedo ocultar carpetas, y si quiero acceder cd ..)
``` bash
python -m venv app_matricula_python
```

## 5. acceder y activar nuestro entrono virtual (Scripts siempre con mayuscula al inicio)
```bash
source app_matricula_python/Scripts/activate
```
## 6. para desactivar:
`deactivate`
## 7. (es como el ´playstore de python) es una dependencia de python que me ayuda a instalar librerias de python
```bash
pip list
```
## 8. para instalar una libreria dentro de mi proyecto (se pone el nombre del pakete)
```bash
pip install 
```