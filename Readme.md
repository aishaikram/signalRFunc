# A function API using SignalR outbinding
The function API index is an http triggered function and when triggered from web browser using local host end point for index /api/index will use html page to display the output of another function Broadcast which is time triggered (5 sec) binded to SignalR service configured using connection string from Azure signalR service. The html page output display the real time stars on a github repo and auto updating the webpage

## created by: Aisha Ikram (following a tutorial of MS learn)
https://learn.microsoft.com/en-gb/azure/azure-signalr/signalr-quickstart-azure-functions-csharp