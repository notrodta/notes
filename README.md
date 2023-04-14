
Fri Apr 14 2023 10:05:37 GMT-0400 (Eastern Daylight Time) | GetUsers.js: {"clientMessage":"Something went wrong: Cannot query field \"test\" on type \"User\".","requestId":"{\"appName\":\"Market\",\"sid\":\"D123456\",\"appVersion\":\"1\"}","clientTimestamp":"2023-04-14T14:05:37.365Z"}
Fri Apr 14 2023 10:05:48 GMT-0400 (Eastern Daylight Time) | Form.js: {"clientMessage":"adding user!","requestId":"{\"appName\":\"Market\",\"sid\":\"D123456\",\"appVersion\":\"1\"}","clientTimestamp":"2023-04-14T14:05:48.180Z"}


*************************************

Tue Apr 11 2023 16:42:19 GMT-0400 (Eastern Daylight Time) | {"appName":"Mm","sid":"D123456","appVersion":"1"}: {"clientMessage":"This is logging test!","requestId":"","clientTimestamp":"2023-04-11T20:42:19.688Z"}

Tue Apr 11 2023 16:44:02 GMT-0400 (Eastern Daylight Time) | {"appName":"Mm","sid":"D123456","appVersion":"1"}: {"clientMessage":{"e":{"componentStack":"\n    at ButtonComponentForceError (webpack-internal:///./pages/index.tsx:95:15)\n    at $44d7e150ebc754d2$export$e926676385687eaf (webpack-internal:///../../node_modules/react-error-boundary/dist/react-error-boundary.module.js:30:1)\n    at Index (webpack-internal:///./pages/index.tsx:63:11)\n    at main\n    at CustomApp (webpack-internal:///./pages/_app.tsx:12:11)\n    at PathnameContextProviderAdapter (webpack-internal:///../../node_modules/next/dist/shared/lib/router/adapters.js:62:11)\n    at ErrorBoundary (webpack-internal:///../../node_modules/next/dist/compiled/@next/react-dev-overlay/dist/client.js:301:63)\n    at ReactDevOverlay (webpack-internal:///../../node_modules/next/dist/compiled/@next/react-dev-overlay/dist/client.js:850:919)\n    at Container (webpack-internal:///../../node_modules/next/dist/client/index.js:61:1)\n    at AppContainer (webpack-internal:///../../node_modules/next/dist/client/index.js:171:11)\n    at Root (webpack-internal:///../../node_modules/next/dist/client/index.js:346:11)"},"logData":"Exception was thrown!"},"requestId":"","clientTimestamp":"2023-04-11T20:44:02.565Z"}

Mon Apr 10 2023 14:45:00 GMT-0400 (EDT) | {"appName":"Mm","sid":"D123456","appVersion":"1"}: {"clientMessage":{"stack":"ReferenceError: unknownvar is not defined\n    at clickhandler (http://localhost:8080/:14:5)\n    at HTMLButtonElement.onclick (http://localhost:8080/:20:34)","message":"unknownvar is not defined","name":"ReferenceError","logData":{"errorMsg":"Uncaught ReferenceError: unknownvar is not defined","url":"http://localhost:8080/","line":14,"column":5}},"requestId":"","clientTimestamp":"2023-04-10T18:45:00.837Z"}

********************************

a_LogOnClientAndServer.js 

Mon Apr 10 2023 14:36:17 GMT-0400 (EDT) | : log message from server

Mon Apr 10 2023 14:36:30 GMT-0400 (EDT) | client: {"clientMessage":"Random User!! rand function at rand file","requestId":"","clientTimestamp":"2023-04-10T18:36:30.899Z"}

Mon Apr 10 2023 14:36:30 GMT-0400 (EDT) | client: {"clientMessage":"message from the client!!!!!!!","requestId":"","clientTimestamp":"2023-04-10T18:36:30.914Z"}

Mon Apr 10 2023 14:36:31 GMT-0400 (EDT) | client: {"clientMessage":{"x":5,"y":7},"requestId":"","clientTimestamp":"2023-04-10T18:36:30.915Z"}


******************************

b_LogClientExceptionToServer.js 

Mon Apr 10 2023 14:44:18 GMT-0400 (EDT) | : log message from server

Mon Apr 10 2023 14:45:00 GMT-0400 (EDT) | onerrorLogger: {"clientMessage":{"stack":"ReferenceError: unknownvar is not defined\n    at clickhandler (http://localhost:8080/:14:5)\n    at HTMLButtonElement.onclick (http://localhost:8080/:20:34)","message":"unknownvar is not defined","name":"ReferenceError","logData":{"errorMsg":"Uncaught ReferenceError: unknownvar is not defined","url":"http://localhost:8080/","line":14,"column":5}},"requestId":"","clientTimestamp":"2023-04-10T18:45:00.837Z"}
