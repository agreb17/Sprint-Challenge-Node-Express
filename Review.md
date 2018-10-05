# Review Questions

## What is Node.js?

it is a JavaScript environment that allow us to execute JavaScript apps outside the browser

## What is Express?

it is ultimately just a Node.js module, but it allows us to build web apps, serve single page apps, and build restful web services that work with JSON, among other things.

## Mention two parts of Express that you learned about this week.

learned about Routing and Middleware

## What is Middleware?

they are functions that get req and res objects and can operate on them and return the res or call the next() middleware.

## What is a Resource?

All data in the DB that can be managed by the API... So everything

## What can the API return to help clients know if a request was successful?

return status codes

## How can we partition our application into sub-applications?

by using Router

## What is express.json() and why do we need it?

it is a built-in middleware function that parses incoming requests with JSON payloads
