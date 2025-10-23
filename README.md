# Python Complex Dynamics

Repositorio con notebooks y recursos para el estudio de dinámicas complejas (mapas y planos de parámetros), desarrollado como parte de trabajo académico.

Contenido principal
- `cuencas-atraccion.ipynb` — Dibujo de algunas cuencas.
- `plano-de-parametros.ipynb` — Cálculo y visualización de planos de parámetros.
- `fuentes mathematica/Plano_parametros_Newton.nb` — Fuentes en Mathematica (si usas Mathematica).
- `img/` — Imágenes y figuras usadas en los notebooks.
- `requirements.txt` — Dependencias Python utilizadas.

Requisitos
- Python 3.10+ (recomendado)
- Para reproducir los notebooks: Jupyter Notebook / JupyterLab
- Si necesitas abrir los archivos de la carpeta `fuentes mathematica`, se requiere Wolfram Mathematica.

Instalación rápida (Windows, PowerShell)

1. Crear y activar un entorno virtual:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Instalar dependencias:

```powershell
pip install --upgrade pip
pip install -r requirements.txt
```

Uso
- Lanzar Jupyter y abrir el notebook deseado:

```powershell
jupyter notebook
# o
jupyter lab
```

Notas
- Los notebooks contienen código y celdas con texto explicativo; ejecuta las celdas en orden.
- Los requisitos listados en `requirements.txt` incluyen paquetes como numpy, matplotlib y sympy.
- Si vas a reproducir figuras a alta resolución o usar GPU (si aplica), ajusta las configuraciones en los notebooks.

Contacto
- Autor: Victor (repositorio: vicgalilea95)

Licencia
- Sin licencia especificada. Añade un archivo `LICENSE` si quieres aclarar los términos de uso.
