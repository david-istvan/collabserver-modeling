<img src="https://github.com/david-istvan/lowkey/blob/main/assets/lowkey-logo.png" width="200">

A low-level and transparent framework for collaborative modeling.

[![License](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Build Status](https://travis-ci.com/david-istvan/lowkey.svg?branch=main)](https://travis-ci.com/david-istvan/lowkey)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=david-istvan_lowkey&metric=alert_status)](https://sonarcloud.io/dashboard?id=david-istvan_lowkey)

# Repository structure

- [/lowkey](https://github.com/david-istvan/lowkey/tree/main/lowkey) - Main project.
  -  [/collabtypes](https://github.com/david-istvan/lowkey/tree/main/lowkey/collabtypes) - Type system for collaborative modeling.
  -  [/lww](https://github.com/david-istvan/lowkey/tree/main/lowkey/lww) - Low-level CRDT system.
  -  [/server](https://github.com/david-istvan/lowkey/tree/main/lowkey/server) - Websocket-based client-server infrastructure.
- [/lowkey-examples](https://github.com/david-istvan/lowkey/tree/main/lowkey-examples) - Examples.

# References

## Metamodeling

<img src="https://raw.githubusercontent.com/david-istvan/collabserver-modeling/main/docs/modelverse.PNG?raw=true"/>

Source: [Van Mierlo, Barroca, Vangheluwe, Syriani, Kühne. Multi-Level Modelling in the Modelverse. Proceedings of MULTI 2014.](http://miso.es/multi/2014/proceedings_MULTI.pdf#page=89)


## CRDT specifications

[Shapiro M, Preguiça N, Baquero C, Zawirski M. A comprehensive study of convergent and commutative replicated data types (Doctoral dissertation, Inria–Centre Paris-Rocquencourt; INRIA)](https://hal.inria.fr/file/index/docid/555588/filename/techreport.pdf)

