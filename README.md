# SIMATIC Automation Tool application example

This example shows how to use the Industrial Edge App “SIMATIC Automation Tool” 

- [SIMATIC Automation Tool application example](#simatic-automation-tool-application-example)
  - [Description](#description)
    - [Overview](#overview)
    - [General task](#general-task)
  - [Requirements](#requirements)
    - [Prerequisities](#prerequisities)
    - [Used components](#used-components)
    - [TIA Project](#tia-project)
  - [Configuration steps](#configuration-steps)
  - [Usage](#usage)
  - [Documentation](#documentation)
  - [Contribution](#contribution)
  - [Licence and Legal Information](#licence-and-legal-information)


## Description

### Overview

This document describes how to scan the network and displays all devices with detailed information’s within the Industrial Edge environment.

![overview](docs/graphics/Overview.PNG)

### General task

The example scans the network and displays all devices with detailed information’s in the Automation Tool App. The selected PLC’s are switched to STOP mode for doing a firmware update followed by a program update. The used firmware and program files are handled by the file manager. TIA Portal used to generate program files to upload them to the file manager.

## Requirements

### Prerequisities

- Access to an Industrial Edge Management System (IEM)
- Onboarded Industial Edge Device on IEM
- Configured Layer 2 access on Edge Device
- Installed Apps Device Scanner, SIMATIC Automation Tool
- Edge device is connected to PLC
- TIA portal project loaded on PLC (e.g. for filling application)
- Google Chrome (Version ≥ 72) or Firefox (Version ≥ 62)

### Used components

- Industrial Edge Management (IEM) V1.2.0-36
- Device Scanner 1.1.0
- SIMATIC Automation Tool 1.0.5
- Industrial Edge Device V 1.2.0-57
- TIA Portal V16
- S7-1511
- Web browser (Mozilla or Chrome)

### TIA Project

The used TIA Portal project can be found in the [miscellenous repository](https://github.com/industrial-edge/miscellenous) under the following name and is also used for several further application examples:

-[tia-tank-application.7z](https://github.com/industrial-edge/miscellaneous/blob/main/tank%20application/tia-tank-application.7z)

## Configuration steps

You can find the further information about the following steps in the [docs](docs/Installation.md)
- Configure IED Layer 2 access
- Configure SIMATIC Automation Tool

## Usage

Once the SIMATIC Automation Tool App is configured, you can scan the Network, display all PLC´s, Stop the PLC´s and update the firmware.

## Documentation

You can find further documentation and help in the following links
  - [Industrial Edge Hub](https://iehub.eu1.edge.siemens.cloud/#/documentation)
  - [Industrial Edge Forum](https://www.siemens.com/industrial-edge-forum)
  - [Industrial Edge landing page](https://new.siemens.com/global/en/products/automation/topic-areas/industrial-edge/simatic-edge.html)
  
## Contribution

Thank you for your interest in contributing. Anybody is free to report bugs, unclear documentation, and other problems regarding this repository in the Issues section.
Additionally everybody is free to propose any changes to this repository using Pull Requests.

If you are interested in contributing via Pull Request, please check the [Contribution License Agreement](Siemens_CLA_1.1.pdf) and forward a signed copy to [industrialedge.industry@siemens.com](mailto:industrialedge.industry@siemens.com?subject=CLA%20Agreement%20Industrial-Edge).

## Licence and Legal Information

Please read the [Legal information](LICENSE.md).
