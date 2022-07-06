title Notes - SPA New Note


User->Browser: User inputs note and submits

Browser->Server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa

note left of Browser: Submits JSON data using code from spa.js

Server-->Browser: {"message": "note created"}

note left of Browser: Return HTTP 201 Sent
