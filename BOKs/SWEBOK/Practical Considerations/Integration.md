---
tags:
  - swebok/practical-consideration
SWEBOK_KA: "[[Software Construction]]"
---
Concerns related to construction integration include:
- planning the sequence in which components will be integrated
- identifying what hardware is needed
- creating scaffolding to support interim versions of the software
- determining the degree of testing and quality work performed on components before they are integrated
- determining points in the [[project]] at which interim versions of the [[software]] are tested

## Phased approach vs Incremental approach

| Phased approach (aka "big bang")                                                                                            | Incremental Approach                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| --------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| entails delaying the integration of component software parts until all parts intended for release in a version are complete | [[Developer]]s write and test a program in small pieces and then combine the pieces one at a time<br><br>Offers easier error location, improved progress monitoring, more fully tested units, earlier product delivery, improved customer relations.<br><br>Additional test infrastructure, such as stubs, drivers, and mock objects, are usually needed to enable incremental integration.<br><br>By building and integrating one unit at a time (for example, a class or component), the construction process can provide early feedback to developers and customers |
