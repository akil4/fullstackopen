```mermaid
    sequenceDiagram
        participant browser
        participant server
        
        browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
        server activated
        server-->>browser: 201 created {"message":"note created"}
        server deaactivated
        
        Note left of browser: Browser executes event handler and renders the display
    
```
