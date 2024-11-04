# Supported Ballerina language features

This document provides a high-level overview of the [Ballerina](https://ballerina.io) language features that are supported in the Kola low code environment.  


## Core Language Features

| Language Feature | Availability | Note                                                                                            |
| :---:   |:-------------|:------------------------------------------------------------------------------------------------|
|Functions| Yes          | A limited set of function signature syntax is supported.                                        |
|Service Declaration| Yes          | A limited set of Service declaration syntax is supported.                                       |
|Types| Yes          | Readonly entity relationship diagram available. Editing capabilities will be available in the M4.|
|Configurables| Yes          |                                                                                                 |
|Listeners| Yes          | A limited set of Listeners are supported. See Note 1.                                           |
|Global Variables/Contests| No           | Will be available in the M5.                                                                    |
|Workers| No           | Will be available in the M4.                                                                    |



???+ info "Note1"
      M3 Supports the following service types.

     1. HTTP Service
     2. Messaging connectors (Kafka, RabbitMQ, NATS, MQTT, JMS, ASB)
     3. GitHub Events Trigger
     4. Salesforce Events Trigger

## Supported Statements
| Statement                          | Availability | Note                                                                                      |
|------------------------------------|--------------|-------------------------------------------------------------------------------------------|
| Variable Definition Statement      | M3           | Only simple type binding (single variable statements) is supported in M3.                 |
| Assignment Statement               | M3           | Only simple type binding (single variable statements) is supported in M3.                 |
| If Statement                       | M3           |                                                                                           |
| While Statement                    | M3           |                                                                                           |
| Foreach Statement                  | M3           | Only simple type binding (single variable statements) is supported in M3.                 |
| Break Statement                    | M3           |                                                                                           |
| Continue Statement                 | M3           |                                                                                           |
| Fail                               | M3           |                                                                                           |
| Panic                              | M3           |                                                                                           |
| Lock                               | M4           |                                                                                           |
| Fork Statements                    | M4           |                                                                                           |
| Wait Statements                    | M4           |                                                                                           |
| Do-on-Fail (Error handling)        | M4           |                                                                                           |
| Transaction Statement              | M4           |                                                                                           |
| Retry and Retry-Transaction        | M4           |                                                                                           |
| Match Statement                    | M4           |                                                                                           |
| Worker Interaction Statements      | M5           |                                                                                           |



