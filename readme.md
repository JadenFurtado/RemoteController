# RemoteController

Based of the <a href="https://github.com/rowanthorpe/ws-repl">REPL</a> project by <a href="https://github.com/rowanthorpe">@rownthorpe</a>

# Step 1:
Install websocketd and run the following:

./websocketd --address=127.0.0.1 --port=8080 sh -c 'while IFS= read -r input; do python <python_file> "${input}"; done'

# Step 2:
Open the server file on the system and use the console to control the laptop

