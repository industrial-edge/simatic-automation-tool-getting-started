# SIMATIC Automation Tool application example
This example shows how to use the Industrial Edge App “SIMATIC Automation Tool”.

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
This document describes how to scan the network and display all devices with detailed information within the Industrial Edge environment.

![overview](docs/graphics/Overview.PNG)

### General task
The example scans the network and displays all devices with detailed information in the SIMATIC Automation Tool app. The selected PLC is switched from STOP to RUN mode. Then the IP address is switched. The last chapter describes how a firmware update can be commissioned.

## Requirements
### Prerequisities
- Access to an Industrial Edge Management System (IEM)
- Onboarded Industial Edge Device on IEM
- Configured Layer 2 access on Edge Device
- Installed Apps: Device Scanner DCP Service, Device Scanner IP Service, SIMATIC Automation Tool
- Edge device is connected to PLC
- Google Chrome (Version ≥ 72) or Firefox (Version ≥ 62)

### Used Components
- Device Scanner IP Service V1.3.0
- Device Scanner DCP Service V1.3.0

### Used components
- Industrial Edge Management (IEM) V1.2.0-36
- Device Scanner IP Service V1.3.0
- Device Scanner DCP Service V1.3.0
- SIMATIC Automation Tool 1.4.0
- Industrial Edge Device V1.2.0-57
- S7-1511
- Web browser (Mozilla or Chrome)

## Configuration steps
You can find the further information about the following steps in the [docs](docs/Installation.md):
- [Configure Device Layer 2 access](docs/Installation.md#configure-device-layer-2-access)
- [Configure SIMATIC Automation Tool](docs/Installation.md#configure-simatic-automation-tool)

## Usage
Once the SIMATIC Automation Tool app is configured, you can scan the network, display all PLC´s, stop the PLC´s and update the firmware.

## Documentation
You can find further documentation and help in the following links
  - [Industrial Edge Hub](https://iehub.eu1.edge.siemens.cloud/#/documentation)
  - [Industrial Edge Forum](https://www.siemens.com/industrial-edge-forum)
  - [Industrial Edge landing page](https://new.siemens.com/global/en/products/automation/topic-areas/industrial-edge/simatic-edge.html)
  
## Contribution
Thank you for your interest in contributing. Anybody is free to report bugs, unclear documentation, and other problems regarding this repository in the Issues section.
Additionally everybody is free to propose any changes to this repository using Pull Requests.

If you haven't previously signed the [Siemens Contributor License Agreement](https://cla-assistant.io/industrial-edge/) (CLA), the system will automatically prompt you to do so when you submit your Pull Request. This can be conveniently done through the CLA Assistant's online platform. Once the CLA is signed, your Pull Request will automatically be cleared and made ready for merging if all other test stages succeed.

## Licence and Legal Information
Please read the [Legal information](LICENSE.md).
