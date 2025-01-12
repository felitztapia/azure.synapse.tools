﻿# Changelog - azure.synapse.tools

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

Replacing all properties environment-related fails

## [0.21.0] - 2022-05-30
* Fixed: Support dynamic references from pipeline's execute notebook activity (#13)
* Fixed: `Get-SynapseObjectBy` internal functions to support notebooks
* Added first unit tests

## [0.20.0] - 2022-05-23
* Spark Job Definition objects are supported now

## [0.19.0] - 2022-05-23
* Pretending that Spark pool exists in order to deploy referring objects (#11)

## [0.18.0] - 2022-01-20
* Fixed Stop/Start triggers while publishing (#8)
* Added Start-SynapseTriggers cmdlet

## [0.17.0] - 2022-01-19
* Added cmdlet generates dependencies diagram (Get-SynapseDocDiagram)
* Fixed issue #7: Replacing all properties environment-related fails

## [0.16.0] - 2022-01-15
* Fixed multiple issues (#1)

## [0.15.0] - 2022-01-15
### Added
* Added support for: (being deployed via Rest API)
  * SQL Scripts 
  * KQL Scripts
  * Notebooks

