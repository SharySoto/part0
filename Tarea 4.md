Tarea 4 


sequenceDiagram
    participant  Navegador
    participant  Servidor
    Navegador->>Servidor: Usuario escribe nota y hace clic en "Save"
    Servidor->>Servidor: Procesamiento de solicitud
    Servidor-->>Navegador: Respuesta de creación de nota