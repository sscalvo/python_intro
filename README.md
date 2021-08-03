# Curso Python
Curso introducción a Python

- Instalar python ([https://www.python.org](https://www.python.org/))
- Crear entorno virtual ([https://docs.python.org/3/library/venv.html#module-venv](https://docs.python.org/3/library/venv.html#module-venv))
```
c:\>python -m venv c:\path\to\myenv
```
- Activar entorno virtual:

| **Platform** | **Shell** | **Command to activate virtual environment** |
| --- | --- | --- |
| Unix | bash/zsh | $ source **<venv&gt;**/bin/activate |
| Windows | cmd.exe | C:\\>**<venv&gt;**\Scripts\activate.bat |

- Instalar librerias de **jupyter**:
```
c:\>pip install jupyter notebook
```
- Permitir este entorno como kernel en jupyter
```
c:\>python -m ipykernel install --user --name <nombre_entorno> --display-name "Nombre en jupyter"
```
- Descargar cuaderno N1 - Introducción a python.ipynb
- Lanzar jupyter
```
c:\>jupyter notebook
```
