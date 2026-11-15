Este es un proyecto cuyo entorno virtual está construido con la herramienta uv. A continuación se detalla cómo instalar uv y qué comandos serían necesarios para adaptar las dependencias del entorno a cualquier sistema operativo y cualquier máquina:

1. Instalar uv
 - macOS / Linux: curl -LsSf https://astral.sh/uv/install.sh | sh
 - Windows (PowerShell): powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

# 2. Crear el entorno con las versiones exactas
uv sync --locked

