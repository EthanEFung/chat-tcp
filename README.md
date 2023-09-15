# im

Simple TCP chat room written in go

## commands

- `/name <name>` set user name, otherwise user stays anonymous. 
- `/join <name>` join an existing room or create a room with unique name. User can only be in one room at a time.
- `/rooms` get a list of room names available to join.
- `/msg <msg>` broadcast a message to everyone in a room.
- `quit` disconnects from the chat server

