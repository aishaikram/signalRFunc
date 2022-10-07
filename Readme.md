# A dotnet 6.0 Azure Function API using SignalR service outbinding
The function API index is an http triggered function and when triggered from web browser using local host end point for index /api/index will use html page to display the output of another function Broadcast which is time triggered (5 sec) binded to SignalR service configured using connection string from Azure signalR service. The html page output display the real time stars on a github repo and auto updating the webpage.

- create a SIgnalR service in serveless mode
- use the connection string for the signalR to update in local.setting.json
- Open in VS code and on terminal type "func start" to run - make sure local azurite blob emulator is running as any function other than http triggered would need local storage to run

- use the URL generated for localhost/api/index to run in browser.
- navigate to the github repo url and click star and see the effect

## created by: Aisha Ikram (following a tutorial of MS learn)
https://learn.microsoft.com/en-gb/azure/azure-signalr/signalr-quickstart-azure-functions-csharp