```mermaid
    sequenceDiagram
        participant browser
        participant server
        
        browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
        activate server
        server-->>browser: 201 created {"message":"note created"}
        deactivate server
        
        Note left of browser: Browser executes event handler and renders the display
    
```
