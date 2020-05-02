---
layout: post
title: "What is HTTP?"
date: 2020-05-02 00:00:00 +0100
categories: programming
---

HTTP is a protocol which governs communication over the internet. It’s based on a client-server model in which the client submits a request and the server returns a response. 

A HTTP request is made up of a combination of ‘verbs’ (e.g. GET, POST, PUT, DELETE) which indicate which type of action the client wants to make, and ‘nouns’ (Uniform Resource Locations or URLs) which identify the location of the resource to which the action should be applied. The URL supplied by the client can include parameters which, in the case of a GET request, help to specify the data which is being requested. A request also includes Headers, which can give further information about the request and the type of response which is desired. There are a large number of Headers available and the client can choose those which are relevant to its particular request. There is also a request Body which in some cases can include data, referred to as the Payload (this is often used in POST requests, when the client wants to add a new resource to the server). A browser is a GUI (Graphical User Interface) for making HTTP requests. For example, when you type the name of a domain (e.g. Google or Facebook) into the address bar and hit enter, the browser will generate and send a HTTP request to a web server.

The most common HTTP verbs are:

GET - request data from the server (read-only request)

POST - update the server with a new resource (i.e. new data) provided by the client

PUT - modify an existing resource on the server

DELETE - delete an existing resource on the server

A HTTP response includes a Status Code which indicates which or not the request has been successful (e.g. 200 indicates a successful request), and gives further information if an error has occurred (e.g. 404 means resource not found). The response also includes Headers, and of course it often includes data (particularly if responding to a GET request). It should be noted that the response to a HTTP request is determined by the actual implementation of the web server.

HTTP is a stateless protocol. This means that the server will not store any information about the client, and therefore has nothing to identify the client if the latter should make a subsequent request. As a consequence of this, each time the client makes a request it will have to include a complete set of information to enable the server to handle the request. It cannot expect the server to remember any data which was previously submitted. It’s important to note that although HTTP itself is stateless, session information can still be stored on clients through the use of cookies.