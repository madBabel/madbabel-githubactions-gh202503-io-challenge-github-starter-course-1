## Objetivo

Encontrar el error en un flujos de trabajo.

## Tareas

1. Corregir el workflow 'Workflow Execution' para que los trabajos:
     - **deploy**:       
       - Debería ejecutarse solo después de que el trabajo build se complete con éxito y si la salida build-status del trabajo build es igual a success.
     - **rollback**:       
       - Debería ejecutarse solo después de que el trabajo build se complete con fallo y si la salida build-status del trabajo build es igual a fail.
         

