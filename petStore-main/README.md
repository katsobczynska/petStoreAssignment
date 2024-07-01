Prerequisites
- Apache JMeter installed
- Newman installed

1. Extract files
2. To run Postman Tests, open any command line editor, choose directory in which files were extracted and run following commands:

newman run uct.postman_collection.json --delay-request 30 -g workspace.postman_globals.json

newman run security.postman_collection.json -g workspace.postman_globals.json

newman run functional.postman_collection.json -g workspace.postman_globals.json

Each test run would generate report in command line.

3. To run Jmeter Performance Test Plan, open extracted jmx file(petstore.perf) in Jmeter and run the test. Aggregate Report listener would produce test report, which can be exported to csv file.
