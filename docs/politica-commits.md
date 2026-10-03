# Política de commits

## Formato del mensaje

Los mensajes seguirán el formato:

tipo: descripción breve del cambio

La descripción se escribirá en español, con un verbo de acción
y suficiente claridad para identificar el cambio realizado.

## Tipos de commits

- feat: agregar una funcionalidad.
- fix: corregir un error.
- docs: crear o actualizar documentación.
- test: agregar o modificar pruebas.
- refactor: reorganizar código sin cambiar su comportamiento.
- ci: modificar el pipeline de integración continua.
- chore: realizar tareas de mantenimiento.

## Ejemplos

- feat: agregar búsqueda de usuarios
- fix: corregir validación de correo
- docs: documentar politica de commits
- test: agregar prueba de creación de usuario

## Reglas

1. Cada commit debe representar un cambio concreto.
2. Evitar mensajes generales como "cambios" o "actualización".
3. Revisar git status y git diff --cached antes de hacer el commit.
4. Incluir únicamente los archivos necesarios para el cambio.
5. No incluir contraseñas, tokens, entornos virtuales ni archivos temporales.
6. Trabajar en ramas feature/*, fix/* o docs/* según el cambio.
7. Enviar los cambios mediante un pull request hacia develop.
8. Solicitar la aprobación de otro integrante antes de integrar el PR.
9. Reservar la integración de develop hacia main para las entregas.