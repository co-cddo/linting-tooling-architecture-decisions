# The rails application will be hosted on PaaS

## Creation Date
15/12/22

## Decision Date
15/12/22

## Status
Accepted

## Context
Heroku is simple to set up as it allows you to have automatic deployments when changes are merged to a main branch on GitHub, however it no longer has a free tier.   

Render can also be set up in the same way, but we’ve found it to be very slow to load when using the free version.  

We already have a CDDO account for GOV.UK PaaS and have deployed an app on there before so have some experience of how it works.   

[PaaS will be decommissioned](https://gds.blog.gov.uk/2022/07/12/why-weve-decided-to-decommission-gov-uk-paas-platform-as-a-service/) in late 2023 / early 2024, so we will need to choose a different platform for the production version.  

## Decision
We will deploy the rails host application on PaaS. 
