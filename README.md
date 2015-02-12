# Pragmatic RESTful API

Article is about best practices in designing/architecting/implementing pragmatic RESTful APIs

## Basic Requirements

* It should use web standards.
* It should be developer friendly - simple, intuitive and consistent & well documented.
* It should provide enough flexibility to power majority of the UI frameworks.
* It should be efficient, while maintaining balance with the other requirements.

## Rules
* Nouns and NO Verbs
* Resource & its Association
* URL Complexity
* Response Format
* Error Format
* Status Codes

## Infrastucture Schematic
* Load Balancers
 * Auto Scale (Spikes)
* Central Cache Management
* Central Session Management
* Central Log Management
* Central Threat Management
* Multi Tenancy (App Key/Secret)
* Central Tool Management
* Central DB Management
* Operational Intelligence

## References
* [Architectural Styles and the Design of Network-based Software Architectures] by [Roy Fielding]
* [REST]

[Roy Fielding]:http://roy.gbiv.com
[Architectural Styles and the Design of Network-based Software Architectures]:http://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm
[REST]:https://en.wikipedia.org/wiki/Representational_state_transfer
