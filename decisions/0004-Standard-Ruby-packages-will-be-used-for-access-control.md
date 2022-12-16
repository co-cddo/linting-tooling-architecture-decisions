# Standard Ruby packages will be used for access control

## Creation Date
15/12/22

## Decision Date
15/12/22

## Status
Accepted

## Context
Some functionality will need to be restricted to certain users due to licensing issues.  

There are a number of Ruby packages (gems) that can add authentication and authorisation functionality to Rails. 
For example, [Devise](https://github.com/heartcombo/devise) provides username and password authentication out of the box and can be easily 
enhanced/configured to use more sophisticated authentication systems such as OAUTH2. 
[Pundit](https://github.com/varvet/pundit) provides fine-grained authorisation control where access to pages and components of pages can be controlled.

## Decision
Standard Ruby packages will be used to control access to the applications.  
