Tarea 6


graph TD;
    A[Navegador] -->|1. Usuario escribe nueva nota y hace clic en 'Guardar'| B[Aplicación de Notas - SPA];
    B -->|2. Procesa la solicitud de creación de nota| C[Servidor];
    C -->|3. Guarda la nueva nota en la base de datos| D[Base de Datos];
    D -->|4. Confirma la creación de la nota| C;
    C -->|5. Envia respuesta de éxito| B;
    B -->|6. Actualiza la interfaz de usuario| A;