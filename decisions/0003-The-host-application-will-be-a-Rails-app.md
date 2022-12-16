# The host application will be a Rails app

## Creation Date
15/12/22

## Decision Date
15/12/22

## Status
Accepted

## Context
An application is required to mount the Rails engine. The application will provide a central resource where API documents can be loaded and run against the NPM package to determine compliance with the linting rules.  

Ruby on Rails is widely used within GOV.UK and is easy to maintain and extend. It provides a web interface that is dynamically generated based on business rules defined within the application code.  

The application will also act as a demonstration of how the engine can be mounted and used.  


## Decision
A Ruby on Rails host application will be used to provide a central interface to the NPM package.  
