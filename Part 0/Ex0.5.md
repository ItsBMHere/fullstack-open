title Notes - Single Page App Version


Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa

Server-->Browser: HTML code

Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css

Server-->Browser: Stylesheet code

Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js

Server-->Browser: JS code

note left of Browser: JS code requests JSON data from server

Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json

Server-->Browser: Note JSON data

note left of Browser: JSON data is rendered by event handler\n to dynamically display
