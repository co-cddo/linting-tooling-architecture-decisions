# Sensitive JSON resources will be encrypted following the JWE standard

## Creation Date
15/12/22

## Decision Date
15/12/22

## Status
Accepted

## Context
Currently, the main concern is the JSON configuration file supplied by 42Crunch. The content of this file is not to be shared.  

[JWE](https://www.rfc-editor.org/rfc/rfc7516) provides a standard for encrypting JSON objects. It is therefore ideal for encrypting the 42Crunch file. There are Ruby packages that make creating and manipulating JWE files straightforward.  

Once the file is encrypted a key must be stored and shared. [Ruby on Rails has a credentials system](https://edgeguides.rubyonrails.org/security.html#custom-credentials) that provides a way of securing the JWE key and sharing access.  

## Decision
JSON resources that require securing will be encrypted following the JWE standards. The encryption key(s) will be stored and accessed via the Rails credential system. 
