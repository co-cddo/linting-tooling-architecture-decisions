# The ruleset will continue to be published as an NPM package

## Creation Date
15/12/22

## Decision Date
15/12/22

## Status
Accepted

## Context
The ruleset is currently published as an NPM package. 
This makes it easy to run from a CLI or in a CI pipeline, 
as most CI solutions allow for NPM packages to be installed and run. 
It also means we can use jest for automated tests for our rules.

## Decision
The ruleset will be published as an NPM package.
