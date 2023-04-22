### 0.4: New note diagram

:point_right: POST https://studies.cs.helsinki.fi/exampleapp/new_note | Payload: note: "some note"

:point_left: 
Code: 302: Redirect to /exampleapp/notes

:point_right:
GET https://studies.cs.helsinki.fi/exampleapp/notes

:point_left: ...

### 0.5: Single page app diagram

:point_right: GET https://studies.cs.helsinki.fi/exampleapp/spa

:point_left: Response Code 200

:point_right: spa.js Status Code: 304 (Not modified) & main.css Status Code 304

:point_right: GET https://studies.cs.helsinki.fi/exampleapp/data.json

### 0.6: New note in Single page app diagram

:point_right: POST https://studies.cs.helsinki.fi/exampleapp/spa | Payload represented in JSON format

:point_left: Code 201 : Created
