# django_chat_app
django_chat_app is a simple chat server.It has two pages:
   --> An index view that lets you type the name of a chat room to join.
   --> A room view that lets you see messages posted in a particular chat room.
   
The room view uses a WebSocket to communicate with the Django server and listen for any messages that are posted.
