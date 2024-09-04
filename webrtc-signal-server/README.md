# WebRTC Signal Server

Handles connecting peers together using a "peer ID", a string assigned by the server.

This server is only a switchboard for routing the bits of handshake data needed establish a WebRTC
P2P connection. Once a P2P connection is established between two clients, data flows directly
between them without going through this server.
