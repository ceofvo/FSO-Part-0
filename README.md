# FSO-Part-0

### Process & diagram depicting the situation, where user creates a new note using the single page version of the app.

title Single Page App   

browser->server: HTTP POST https://fullstack-exampleapp.herokuapp.com/new_note_spa

note over browser:<br>
request contains the new note as JSON-data<br>
contains the content of the note (content)<br>
and the timestamp (date)<br>
end note

server-->browser: Status Code: 201 Created

note over browser:<br>
browser starts executing<br>
JavaScript code it fetched from the server<br>
event handler creates a new note, <br>
adds it to the notes list<br>
rerenders the note list on the page<br>
end note

browser->server: sends the new note to the server

![Process Diagram](https://github.com/ceofvo/FSO-Part-0/blob/master/Process%20Diagram.PNG)
