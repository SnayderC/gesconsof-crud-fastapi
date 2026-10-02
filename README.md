# gesconsof-crud-fastapi

## Sobre este repositorio
Snayder Cedeño
Domeniza Piza
Steven Barona
Kevin Barboza 
Brayan Mosquera
Christopher Aguiño

## Proyecto base
Basado en: https://github.com/Pytest-with-Eric/pytest-fastapi-crud-example

## Requisitos
- Python 3.12.10 (instalador `.exe` de python.org)
- Git

[Escribe aquí en una frase qué pasa si se usa Python 3.14]

## Instalación (Windows con Git Bash)

```bash
git clone https://github.com/SnayderC/gesconsof-crud-fastapi.git
cd gesconsof-crud-fastapi
/c/Users/TU_USUARIO/AppData/Local/Programs/Python/Python312/python.exe -m venv venv
source venv/Scripts/activate
python --version
pip install -r requirements.txt
pytest -v
```

Para levantar la API:

```bash
uvicorn app.main:app --reload
```

Documentación interactiva: http://localhost:8000/docs

## Reglas de colaboración
- Ramas `main` y `develop` protegidas: no se permite push directo.
- Nombres de ramas: `feature/descripcion-corta` para mejoras, `fix/descripcion-corta` para errores, `docs/descripcion-corta` para documentación.
- Todo Pull Request va hacia `develop` y requiere 1 aprobación de otro integrante.
- `main` solo recibe cambios desde `develop` al publicar un release.
- Los commits siguen la política definida por el grupo (ver sección de commits).

---