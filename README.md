# chat-room
Simple CLI ChatRoom write in python
* Original source:
https://github.com/abraarahmed/multi-client-chatroom

## Usage
1. Install dependencies
> pip3 install -r requirements.txt
2. Run server script
> python3 chat_server.py
3. Start server
    - Enter port number
    - Enter admin password
4. Run client script
> python3 chat_client.py [server_ip] [server_port]

## Client Options
```
/u [username]                      - Change the username
/p                                 - Change the password
/c [room_name]                     - (Admin) Create a new room
/j [room_name]                     - Join a room
/l [room_name]                     - Leave a room
/cp [room_name] [room_password]    - (Admin) Create a new private room
/jp [room_name]                    - Join a private room
/cd [room_name]                    - Change default room
/list                              - List all the rooms on the server
/users                             - List all the users on the server
/public <[room_name]> [message]    - Sends a message to any room you are a part of
/private @[username] [message]     - Send a private (encrypted) message to any user
/logout                            - Disconnect from the server
```
