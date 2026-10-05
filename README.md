# Practica de conflicto Git

Este repo contiene dos ramas con cambios incompatibles en `Program.cs`.

- `main`: saluda al grupo.
- `practica/conflicto`: saluda a la persona.

Para provocar el conflicto, desde `main` ejecuta `git merge practica/conflicto`. Resuelve los marcadores en `Program.cs`, conserva ambos saludos, compila con `dotnet build` y confirma la resolución.
