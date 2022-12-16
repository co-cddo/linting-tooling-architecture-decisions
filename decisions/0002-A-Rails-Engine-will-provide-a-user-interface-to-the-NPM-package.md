# A Rails Engine will provide a user interface to the NPM package

## Creation Date
15/12/22

## Decision Date
15/12/22

## Status
Accepted

## Context
The current prototype uses the GOV.UK design package. This is good for creating page content quickly, but is not easily extended and enhanced for production.  

Ruby on Rails is widely used within GOV.UK and easy to maintain and extend. It includes a JavaScript environment and therefore can leverage the NPM functionality.  

Rails Engines provides a way of sharing code packages and mounting them within an existing Ruby web application. The engine can be used in our own applications to provide the user interface, and others can use it to add the functionality to their own Ruby applications.  

It is also possible to split out functionality from a standard Ruby on Rails application, into an Engine. So the main functionality can be initially built in a standard Rails application and the Engine developed at a later stage when we have more experience of how the application will be used and shared. This may well be an easier development pathway.  


## Decision
A Rails engine will be used to provide a shared user interface to the NPM package functionality. The functionality may be initials developed directly within the host app.
