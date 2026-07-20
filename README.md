# Hood Install Station Monitoring

A Windows Forms application for monitoring hood installation operations with robot and PLC integration.

## Overview

This repository presents **ATMC.App.KMC.H5.HoodInstall** as a public portfolio project. The production source code is intentionally not included because the application belongs to an industrial automation environment.

## Project Purpose

The application evaluates pose, registration, and station results during hood installation and presents the process status through an operator interface.

## Key Features

- Hood install station monitoring
- Robot pose and registration checks
- PLC signal and automatic-cycle handling
- Quality result preparation in OK/NG format

## Workflow

1. The operator starts the Windows desktop application at the production station.
2. The application loads station and model settings for the current operation.
3. PLC, robot, sensor, and vision-related results are collected during the production cycle.
4. Registration or measurement results are evaluated against configured tolerances.
5. The dashboard shows station status and the final OK/NG result.
6. Structured result data is prepared for logs, database records, and quality traceability.

## Technologies and Methods

- C# and .NET Framework 4.8
- Windows Forms desktop interface
- Industrial PLC communication
- Robot and automation-system integration
- Vision and 3D registration result processing
- Production result logging
- Database-oriented quality-control records
- Operator dashboard design for manufacturing environments

## Media Placeholders

Screenshots and short demo videos can be added later without exposing source code.

### Screenshots


### Demo Videos


## Confidentiality Note

This repository is documentation-focused. Visual Studio solution files, source code, configuration files, binaries, and build outputs are excluded intentionally. Screenshots and videos should be reviewed before upload so that no private factory data, customer data, IP addresses, credentials, or internal settings are visible.
