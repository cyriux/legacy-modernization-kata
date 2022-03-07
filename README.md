# Legacy Modernization Kata

A kata to practice modernizing a large legacy system


## Problem Statement

You're in charge of modernizing a legacy system for selling tickets for shows like theater, concerts etc.

- The system has approximately 400kLOC (lines of code), built by 8 developers in average over 7+ years. 
- The system is composed of a large monolith plus 3 microservices recently added (Booking, Inventory and Ticketing), which call the legacy through REST calls. 
- The monolith is currently connected to 50+ external partners (through several XML, csv connectors, along with direct access to some of its DB tables).  

weaknesses
- code around catalog of shows is unmaintainable

opportunities
- invoicing is well tested (80% test coverage)

roadmap
- need to invoice in other currencies
- need to list much more complex shows
- many brand new features not similar to anything we've evere done before

technology roadmap
- going towards a service platform

## Your work

Draft a progressive modernization trajectory for the system. You can do it as a brief text memo, or on a diagram (base diagram provided for Excalidraw or as image for any whiteboarding tool in this repo)

You may want to quickly identify potential boundaries inside the monolith, then use some of the following legacy patterns:
- Keep as-is / Extract and repair (as lib or as a service) / Rewrite with Strangler Application pattern / Add microservice
- Legacy Macro-service / Change Data Capture / Legacy Read Model



