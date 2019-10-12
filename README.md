# FSO-Part-0

title Single Page App   

browser->server: HTTP POST https://fullstack-exampleapp.herokuapp.com/new_note_spa

note over browser:
request contains the new note as JSON-data
contains the content of the note (content)
and the timestamp (date)
end note

server-->browser: Status Code: 201 Created

note over browser:
browser starts executing
JavaScript code it fetched from the server
event handler creates a new note, 
adds it to the notes list
rerenders the note list on the page
end note

browser->server: sends the new note to the server
