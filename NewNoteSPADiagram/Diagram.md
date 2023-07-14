```mermaid


sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
   
    deactivate server

    Note right of browser: Using the JS the new note is created, added to the list displaying in the browser and sent to the server

  
```
