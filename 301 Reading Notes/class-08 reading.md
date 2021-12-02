Class 08 Reading APIs

## What does REST stand for?

Representational State Transfer

## REST APIs are designed around a ____.

resources

## What is an identifier of a resource? Give an example.

A URI that uniquely identifies that resource. For example HTTP,JSON

## What are the most common HTTP verbs?

Get Post Put Patch Delete

## What should the URIs be based on?

On nouns aka the resource no verbs.

## Give an example of a good URI.

https://adventure-works.com/**orders

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

To have an API with more request. This is not a good thing because it imposes on the web servers load.

## What status code does a successful GET request return?

A successful GET method typically returns HTTP status code 200 (OK)

## what status code does an unsuccessful GET request return?

404 (Not Found)

## What status code does a successful POST request return?

HTTP status code 201 (Created); f the method updates an existing resource, it returns either 200 (OK) or 204 (No Content)
## What status code does a successful DELETE request return?

HTTP status code 204 (No Content)