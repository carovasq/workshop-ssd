# AGENTS.md — biblioteca-cli

## Proyecto
Aplicación de terminal en Python para gestionar préstamos de libros
(añadir, prestar, devolver, listar). Proyecto educativo.

## Estructura prevista
- biblioteca/core.py     → lógica de negocio (sin input/print)
- biblioteca/storage.py  → lectura/escritura del JSON
- biblioteca/cli.py      → interfaz de línea de comandos
- tests/                 → tests con pytest

## Comandos
- Ejecutar: python -m biblioteca <comando>
- Tests: pytest

## Convenciones
- Python 3.10 o superior, solo biblioteca estándar + pytest
- Código y nombres en inglés; mensajes al usuario en español

## Documentos
- Reglas del proyecto: docs/constitution.md
- Especificaciones: specs/

## Límites
- No añadir dependencias sin avisar
- No modificar docs/constitution.md sin permiso

## Al terminar cualquier tarea
- Ejecutar pytest y mostrar el resultado