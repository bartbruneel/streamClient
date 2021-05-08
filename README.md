# Description
This is a Twitch like client for a streaming application written in React. 

It works against a REST API with one endpoint (for CRUD-operations on streams). This endpoint can be mocked using the npm package json-server (https://www.npmjs.com/package/json-server). 

It has authentication using google OAuth. For this a GCP project clientId needs to be provided. 

It receives streams through an rtmp-server (https://www.npmjs.com/package/node-media-server).  
