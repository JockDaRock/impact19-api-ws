# Impact 2019 - Make your first API Call

https://github.com/JockDaRock/impact19-api-ws

# Guide of commands and URLs for the workshop

Before we get started we need to pull down a docker file for an app we will be using later. Use the following command in a terminal window:

```bash
docker pull ciscodevnet/vs-api-ws-code
```

## Postman links we will need

* We will load the link below into Postman Collections

https://raw.githubusercontent.com/JockDaRock/impact19-api-ws/master/Impact%20Postman%20API%20requests%20Workshop.postman_collection.json

<!--* If we have time we will use this one as well

https://raw.githubusercontent.com/CiscoDevNet/IOx-FND-API-App-Deploy-Postman/master/IOx-FND%20API%20App%20Deploy-Undeploy%20Postman.postman_collection.json-->


## Python Samples

Run the following command to bring up our code samples

```
docker run -it -p 127.0.0.1:8443:8443 ciscodevnet/vs-api-ws-code:latest --allow-http --no-auth
```

In a browser Navigate to http://127.0.0.1:8443


