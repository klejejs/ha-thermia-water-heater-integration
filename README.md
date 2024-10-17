# Thermia Heat Pump Integration

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/klejejs/ha-thermia-heat-pump-integration?style=for-the-badge)](https://github.com/klejejs/ha-thermia-heat-pump-integration/releases)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/y/klejejs/ha-thermia-heat-pump-integration?style=for-the-badge)](https://github.com/klejejs/ha-thermia-heat-pump-integration/commits)
[![License](https://img.shields.io/github/license/custom-components/blueprint.svg?style=for-the-badge)](LICENSE)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

Thermia Heat Pump Integration for Home Assistant. Depends on [Python Thermia Online API](https://github.com/klejejs/python-thermia-online-api).

_Component to integrate with [Thermia Heat Pump](https://github.com/klejejs/ha-thermia-heat-pump-integration)._

**This component will set up the following platforms.**

Platform | Description
-- | --
`water_heater` | Thermia Heat Pump integration
`binary_sensor` | Operational and power status binary sensors
`sensor` | Alarms sensor and different heat pump sensors
`switch` | Hot water and hot water boost switches

## Supported heat pump models:

The integration supports heat pumps that are supported by the underlying [Python Thermia Online API](https://github.com/klejejs/python-thermia-online-api). To see the list of supported heat pumps, please check the list of example heat pump data files in the API repository [here](https://github.com/klejejs/python-thermia-online-api/tree/main/ThermiaOnlineAPI/tests/debug_files).

## Adding support for new heat pump models:

If your heat pump is not working as expected or is not in the supported heat pump list, please follow the instructions in the [Python Thermia Online API](https://github.com/klejejs/python-thermia-online-api/tree/main?tab=readme-ov-file#regarding-unsupported-models) repository to add support for your heat pump model.

## Setup

To set up Thermia Heat Pump Integration, go to Settings -> Integrations -> Add Integration and search for Thermia Heat Pump.

## Installation

Open HACS, go to the Integrations view and search for Thermia Heat Pump Integration.

## Manual Installation

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
2. If you do not have a `custom_components` directory (folder) there, you need to create it.
3. Download the latest release zip file either from repository releases or using this [link](https://github.com/klejejs/python-thermia-online-api/releases/latest/download/thermia.zip).
4. Extract the content of the zip file to the `custom_components` directory (folder) in your HA configuration directory (folder).
5. Restart Home Assistant.

## Contributions are welcome!
