# git-notifications

1) `conn-oriented.py`

This code sets up a WebSocket client that connects to a remote server at `wss://10.122.28.3/restconf/streams/v1/inventory.json`. It uses the Python websocket library to establish the connection and handle incoming and outgoing messages.

The `on_message`, `on_error` and `on_close` functions are callback functions that are called when the WebSocket connection receives a message, encounters an error, or is closed, respectively. The `on_open` function is a callback that is called when the WebSocket connection is established and ready to use.
