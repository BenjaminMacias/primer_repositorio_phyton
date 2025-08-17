# primer_repositorio_phyton

Colección de ejercicios y scripts básicos en **Python** para practicar sintaxis, estructuras de datos, funciones, módulos y pruebas.

## 🧭 Descripción del proyecto
Este repo incluye ejemplos sencillos y reutilizables:
- Scripts de línea de comandos (CLI) para tareas comunes.
- Módulos con funciones utilitarias.
- Notebooks (opcional) para experimentar paso a paso.
- Pruebas unitarias básicas.

> Ideal como primer repositorio para afianzar fundamentos de Python.

---

## 🛠️ Tecnologías utilizadas
- **Lenguaje:** Python 3.10+
- **Gestión de dependencias:** `pip` + `requirements.txt` (si aplica)
- **Pruebas (opcional):** `pytest`
- **Formateo/Lint (opcional):** `black`, `flake8`, `isort`

---

## 🚀 Instalación e inicio rápido

### 1) Clonar y crear entorno virtual
```bash
git clone https://github.com/BenjaminMacias/primer_repositorio_phyton.git
cd primer_repositorio_phyton

# Crear y activar entorno virtual (Windows PowerShell)
python -m venv .venv
. .venv/Scripts/Activate.ps1

# macOS / Linux
# python3 -m venv .venv
# source .venv/bin/activate
2) Instalar dependencias (si existe requirements.txt)
bash
Copiar
Editar
pip install -r requirements.txt
3) Ejecutar un script de ejemplo
Ajusta el nombre del archivo según tu carpeta/ejercicio (por ej. main.py o scripts/saludo.py).

bash
Copiar
Editar
python main.py
# o
python scripts/saludo.py --nombre "Benjamín"
🧪 Pruebas (opcional)
bash
Copiar
Editar
pytest -q
📘 Ejemplos de uso
A) Ejecutar un script CLI
bash
Copiar
Editar
python scripts/operaciones.py --suma 5 7
# → Resultado: 12
B) Usar una función desde un módulo
python
Copiar
Editar
# archivo: demo.py
from utils.matematicas import sumar

print(sumar(2, 3))  # 5
bash
Copiar
Editar
python demo.py
C) Ejecutar un notebook (si existe la carpeta notebooks/)
bash
Copiar
Editar
# Instalar jupyter si no está en requirements
pip install jupyter
jupyter notebook notebooks/intro.ipynb
📂 Estructura sugerida
arduino
Copiar
Editar
primer_repositorio_phyton/
├─ scripts/           # scripts ejecutables (CLI)
├─ utils/             # módulos reutilizables (funciones/clases)
├─ notebooks/         # cuadernos Jupyter (opcional)
├─ tests/             # pruebas unitarias (pytest)
├─ requirements.txt   # dependencias (si aplica)
└─ README.md
📝 Notas
Si cambias el nombre de los scripts o módulos, actualiza los ejemplos de ejecución.

Puedes añadir retos/ejercicios por carpeta (por tema).

Si no utilizas tests/notebooks, elimina las secciones que no apliquen para mantener el README limpio.

makefile
Copiar
Editar
::contentReference[oaicite:0]{index=0}
