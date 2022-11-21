# RemoteController
```
                           _         ___               _             _   _              
                          ( )_      (  _`\            ( )_          (_ )(_ )        
 _ __  __   ___ ___    _  | ,_)  __ | ( (_)  _    ___ | ,_)_ __  _   | | | |   __  _ __ 
( '__/'__`/' _ ` _ `\/'_`\| |  /'__`| |  _ /'_`\/' _ `| | ( '__/'_`\ | | | | /'__`( '__)
| | (  ___| ( ) ( ) ( (_) | |_(  ___| (_( ( (_) | ( ) | |_| | ( (_) )| | | |(  ___| |   
(_) `\____(_) (_) (_`\___/`\__`\____(____/`\___/(_) (_`\__(_) `\___/(___(___`\____(_)   
                                                                                                                                
```
Based of the <a href="https://github.com/rowanthorpe/ws-repl">REPL</a> project by <a href="https://github.com/rowanthorpe">@rownthorpe</a>

# Step 1:
Install websocketd and run the following:

./websocketd --address=127.0.0.1 --port=8080 sh -c 'while IFS= read -r input; do python <python_file> "${input}"; done'

# Step 2:
Open the server file on the system and use the console to control the laptop

