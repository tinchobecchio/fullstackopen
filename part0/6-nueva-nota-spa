```mermaid

sequenceDiagram
    participant browser
    participant server
		
		Note right of browser: El usuario crea la nota, el navegador las renderiza de nuevo y se envia la nota al servidor

		browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: Código de estado HTTP 201
    deactivate server

  ```
