a_LogOnClientAndServer.js 

Mon Apr 10 2023 14:36:17 GMT-0400 (EDT) | : log message from server

Mon Apr 10 2023 14:36:30 GMT-0400 (EDT) | client: {"clientMessage":"Random User!! rand function at rand file","requestId":"","clientTimestamp":"2023-04-10T18:36:30.899Z"}

Mon Apr 10 2023 14:36:30 GMT-0400 (EDT) | client: {"clientMessage":"message from the client!!!!!!!","requestId":"","clientTimestamp":"2023-04-10T18:36:30.914Z"}

Mon Apr 10 2023 14:36:31 GMT-0400 (EDT) | client: {"clientMessage":{"x":5,"y":7},"requestId":"","clientTimestamp":"2023-04-10T18:36:30.915Z"}


******************************

b_LogClientExceptionToServer.js 

Mon Apr 10 2023 14:44:18 GMT-0400 (EDT) | : log message from server

Mon Apr 10 2023 14:45:00 GMT-0400 (EDT) | onerrorLogger: {"clientMessage":{"stack":"ReferenceError: unknownvar is not defined\n    at clickhandler (http://localhost:8080/:14:5)\n    at HTMLButtonElement.onclick (http://localhost:8080/:20:34)","message":"unknownvar is not defined","name":"ReferenceError","logData":{"errorMsg":"Uncaught ReferenceError: unknownvar is not defined","url":"http://localhost:8080/","line":14,"column":5}},"requestId":"","clientTimestamp":"2023-04-10T18:45:00.837Z"}
