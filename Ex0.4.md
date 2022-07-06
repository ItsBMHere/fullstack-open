title Notes - Forms/HTTP POST version


User->Browser: Write note in form and submit

Browser->Server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note

note right of Server: Returns 302 Found

Server-->Browser: Redirect back to exampleapp/notes

Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes

Server-->Browser: HTML code

note left of Browser: Returns HTTP 200\nif successful

Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css

Server-->Browser: Send stylesheet

Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js

Server-->Browser: Send JS code

note right of Browser: JS code requests JSON data

Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json

Server-->Browser: Send "raw" data of notes

note left of Browser: Note data is rendered by event\nhandler and displayed
