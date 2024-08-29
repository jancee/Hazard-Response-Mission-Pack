# Functional Nodes

## Introduction

Here is the basic Node-RED Flow implemented by seeed studio and community developers.

This includes the incoming and outgoing data from the device, and some of the application case base dependencies on the Global and Subflow nodes

## Functional Global Nodes Inventory

| Type | Related equipment | Author | Description | Flow File |
| --- | --- | --- | --- | --- |
| IoT | Basecamp | @Seeed-Studio | The base config nodes of 3 channels RS485 in reComputer r1000. | [JSON](./global/default_rs485_global_nodes.json) |
| IoT | Basecamp | @Seeed-Studio | The base config node of the built-in MQTT network. | [JSON](./global/default_rs485_global_nodes.json) |

## Functional Subflow Inventory

| Type | Related equipment | Author | Description | Flow File |
| --- | --- | --- | --- | --- |
| UI | Basecamp | @Seeed-Studio | | [JSON](./subflow/condition.json) |
| Logic & UI | Basecamp | @Seeed-Studio | Map ui and geofence. It can be used with tracker for location and asset management | [JSON](./subflow/condition.json) |
| Logic | Basecamp | @Seeed-Studio | Good logic judgment node, used to simply do multi-device data condition judgment processing and execution | [JSON](./subflow/condition.json) |
| Virtual Device | Basecamp | @Seeed-Studio | A virtual device node for presenting possible scenarios of a 7-in-1 weather station, with community contributions expected | [JSON](./subflow/7in1-weather-station.json) |
| Device | SenseCAP T1000-E | @Seeed-Studio |  |
| Device | Basecamp | @Seeed-Studio |  |
| Device | Basecamp | @Seeed-Studio |  |
| Device | Basecamp | @Seeed-Studio |  |
| Device | Basecamp <br/>& RS485 Light Controller | @Seeed-Studio | Integrate reComputer R1000, with rs485 light controller. | [JSON](./subflow/rs485-light-controller.json) |
| Device | SenseCAP Data Logger <br/>& Ultrosonic | @Seeed-Studio | Integrate SenseCAP Data Logger, with a ultrosonic sensor. | [JSON](./subflow/sensecap-data-logger-ultrasonic.json) |
| Device | SenseCAP Data Logger <br/>& Tripwire | @Seeed-Studio | Integrate SenseCAP Data Logger, with a tripwire sensor. | [JSON](./subflow/sensecap-data-logger-tripwire.json) |




