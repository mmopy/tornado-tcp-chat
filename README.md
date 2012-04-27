tornado-tcp-chat
================

A simple experiment in doing a TCP connection based chat server with Tornado. The server has two states:

1) AUTH: wait for the user to enter a unique name. Once done they join CHAT.
2) CHAT: Each line of text is sent to all other users connected to the server.

The sample also broadcasts messages when users connect to CHAT (state) and leave CHAT (state)

I wrote this simple to learn something about Python and Tornado.