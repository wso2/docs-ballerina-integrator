# Supported Ballerina language features

This document provides a high-level overview of the [Ballerina](https://ballerina.io) language features that are supported in the Kola low code environment.  


## Core language features

| Language Feature           | Availability | Note                                                                                                  |
|:---------------------------|:-------------|:------------------------------------------------------------------------------------------------------|
| Functions                  | Yes          | A limited set of function signature syntax is supported.                                              |
| Service declaration        | Yes          | A limited set of service declaration syntax is supported.                                             |
| Types                      | Yes          | A read-only entity relationship diagram is available. Editing capabilities will be available with M4. |
| Configurables              | Yes          |                                                                                                       |
| Listeners                  | Yes          | A limited set of listeners are supported. See Note 1.                                                 |
| Global variables/Constants | No           | Will be available with M5                                                                             |
| Workers                    | No           | Will be available with the M4.                                                                        |



???+ info "Note1"
      M3 Supports the following service types.

     1. HTTP service
     2. Messaging connectors (Kafka, RabbitMQ, NATS, MQTT, JMS, ASB)
     3. GitHub events trigger
     4. Salesforce events trigger

## Supported statements
| Statement                     | Availability | Note                                                                                      |
|-------------------------------|--------------|-------------------------------------------------------------------------------------------|
| Variable definition statement | M3           | Only simple type binding (single variable statements) is supported in M3.                 |
| Assignment statement          | M3           | Only simple type binding (single variable statements) is supported in M3.                 |
| If statement                  | M3           |                                                                                           |
| While statement               | M3           |                                                                                           |
| Foreach statement             | M3           | Only simple type binding (single variable statements) is supported in M3.                 |
| Break statement               | M3           |                                                                                           |
| Continue statement            | M3           |                                                                                           |
| Fail                          | M3           |                                                                                           |
| Panic                         | M3           |                                                                                           |
| Lock                          | M4           |                                                                                           |
| Fork statements               | M4           |                                                                                           |
| Wait statements               | M4           |                                                                                           |
| Do-on-Fail (Error handling)   | M4           |                                                                                           |
| Transaction statement         | M4           |                                                                                           |
| Retry and Retry-transaction   | M4           |                                                                                           |
| Match statement               | M4           |                                                                                           |
| Worker interaction statements | M5           |                                                                                           |



