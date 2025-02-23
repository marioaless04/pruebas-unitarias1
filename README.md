# Sistema de Gestión de Tareas - Pruebas Unitarias

Este proyecto implementa un sistema de gestión de tareas con soporte para crear, editar y eliminar tareas.

## Casos de Uso Implementados
1. **Editar una tarea existente**
   - Permite modificar el título y descripción de una tarea.
   - Maneja errores si la tarea no existe o si el título es vacío.

2. **Eliminar una tarea**
   - Permite borrar una tarea existente.
   - Maneja errores si la tarea no existe.

## Pruebas Implementadas
| Prueba | Descripción |
|--------|------------|
| test_edit_task_success() | Verifica que una tarea pueda editarse correctamente. |
| test_edit_task_not_found() | Verifica que el sistema maneje tareas inexistentes al editar. |
| test_edit_task_empty_title() | Valida que no se pueda asignar un título vacío a una tarea. |
| test_delete_task_success() | Verifica la eliminación de una tarea existente. |
| test_delete_task_not_found() | Verifica que no se pueda eliminar una tarea inexistente. |

## Cómo ejecutar las pruebas
```sh
pytest test_task_manager.py
