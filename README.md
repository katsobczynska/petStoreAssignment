Prerequisites

Apache JMeter installed
Newman installed
Extract files
To run Postman Tests, open any command line editor, choose directory in which files were extracted and run following commands:
newman run uct.postman_collection.json --delay-request 30 -g workspace.postman_globals.json

newman run security.postman_collection.json -g workspace.postman_globals.json

newman run functional.postman_collection.json -g workspace.postman_globals.json

Each test run would generate report in command line.
