# i3 Common Schema

Common OpenAPI scehema for i3-based interfaces. Commmunicates the version(s) supported, the current condition of the interface and JWS signature. All interfaces include this common YAML for interoperability purposes between implementations that might support different versions of an interface. For example, System A may support version 2.0 and 1.0 of an interface but needs to talk to System B that only supports version 1.0. In this case, the two systems can use i3 Common Versions information to negotiate a shared version of the interface. Parameters include but are not limited to:

* Major and minor version number 
* Vendor Extension
* Condition Status (e.g., Security Posture, CallSuspicionCondition, LocationCondition etc.)

## Owner

The owner of this repository approves all changes to the repository. 

This repository is owned by the NENA Core Services Committee, i3 Architecture working group.

#### Rules:

Specification Required. 

#### Contact:

[https://www.nena.org/page/911CoreSvcs](https://www.nena.org/page/911CoreSvcs) 

## Version History

### i3 Common Schema v 1.0

An OpenAPI schema for i3 Common Schema was originally defined in NENA-STA-010.3.2021. See https://www.nena.org/page/i3_Stage
