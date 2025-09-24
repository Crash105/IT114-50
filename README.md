#Chatroom Application

##Instructions on how to launch and use the application

##Clone the Github repo, go to the project root and type in seperate terminals
'

####javac Project/serer/Server.java
####java Project.server.Server

####javac Project/client/ClientUI.java
####java Project.client.ClientUI

####The more times you execute the ClientUI code, the more clients you can have in your chatroom application

####Use the following commands for the chatroom application

##flip: Gives the output of randomly throwing Heads or tails
##roll [number]: For example, when you type roll 20, it will generate a random number between one and 20

####whisper: To message a private message to a user do @user_name you want to send to@message you want to send to user. For example @Dan@Hello, good to see you

###mute user: To mute a user meaning you dont want to see there messages, type /mute user
###unmute user: To unmute the user you unmuteed, type /unmute user

###createroom: To create a chatroom, type /createroom [number], the number is an identifier of the chatroom. When you do this, you not only create the room, but automatically join the room. Only people in room can send message beitween eachother

###joinroom: To join a chatroom, type /joinroom [number], the number is an identifier of the chatroom.

##Format messages

###To format messages, put the below symbols between the symbol you want to format

`#r#` ###Turns the color of message red
`#b#` ###Turns the color of message blue
`#g#` ###Turns the color of message green
`--` ###Turns the message to italics
`__` ###Turns the message to underline
`**` ###Turns the message to bold
