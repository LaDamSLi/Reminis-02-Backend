# Reminiscencia - Backend

Este repositorio contiene la lógica del servidor y funciones Cloud Functions para el proyecto "Reminiscencia", alojado en Firebase.

## Características

- Implementación de algoritmos de procesamiento y funciones bajo demanda.
- Servicios HTTP y endpoints para integrar con la base de datos y la App Móvil.

## Flujo de Trabajo (Git Workflow)

Para mantener el código organizado y evitar conflictos en la rama `master`, se debe seguir el siguiente flujo de trabajo:

1. **Crea una nueva rama** partiendo de `master` para cada cambio:
   - Para nuevas características: `git checkout -b feat/nombre-caracteristica`
   - Para arreglos de errores: `git checkout -b fix/nombre-error`
   - Para tareas de mantenimiento: `git checkout -b chore/nombre-tarea`
2. **Desarrolla tus cambios** e incluye descripciones claras en los `commits`.
3. **Publica tu rama**: `git push origin nombre-rama`
4. **Crea un Pull Request (PR)** hacia la rama `master`.
5. Revisa, aprueba y finalmente haz merge del PR para integrar los cambios.
