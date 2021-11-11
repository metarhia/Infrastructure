# Metarhia Command Panel 
## Settings and controls of distributed Metarhia infrastructure

*I suggest all involwed in the development of this model install and review [N|Solid](https://nodesource.com/products/nsolid) panel to review and learn functionality. To prevent reinwentment of a bycicle and to learn good solutions, in case there are amy.*

Control center with GUI, manual controls and scripted configurations input.

A container that consists all required modules for initial setting and configuration of fleet of nodes, DBs and other subsystems. By launch should be able to accept a list of IP addresses/ports, generate private keys for connection to all distributed subsystems, and choose from a list an approximate type and scale of desired system functionality (including general purpose option).

There should be several dublicates of such a center, in case of emergency. This is the most delicate and powerful source of thuth for the entire system, so security measures should be paramaunt.   

## Requited Modules:

1. Authentication 
2. Transport
3. Self-signed certificates generator
4. Third party services configuration and connectors
5. Load Test design, performance and analisys
6. Configuration data storage
7. Logging
8. Sheduling
9. GUI


## Authentication

The module should provide several types of roles and previlege levels

## Transport module

## Self-signed certificates generator

## Third party services connectors

 Cloud hosters, Email services, CDN, payments etc.
 This module should calculate in human undestandable figures of cost/per user and approxiamate overoll fees for 3 party services in several scenarios of traffic fluctuations. AWS and several others have done everything to make this unbearable so, we need conremeasures.

## Configuration data storage

## Logging

## Sheduling

## GUI

The gui should provide:

1. Visualisation of the system statistics in real time
2. Graphical planning and management of configurations with auto predictions of outcome
3. Configuration scripts inputs (with syntax checker)
